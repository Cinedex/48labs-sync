# 48Labs — Project State
> Last updated: 2026-04-21
> Tracks all major systems, their current state, recent refactors, deprecated patterns, and deferred items.
> Claude Code updates this file after any system-level change. Base44 reads this to avoid rebuilding things that exist.

---

## 1. Phase Summary

| Phase | Name | Status |
|---|---|---|
| Phase 1 | Design tokens and standards convergence | ✅ COMPLETE |
| Phase 2 | Sync layer + stability | IN PROGRESS |
| Phase 3 | Feature work | NOT STARTED |

---

## 2. Major Systems — Current State

### Booking Engine ✅

**Entry point:** `createBookingWorkflow(input)` — `@/lib/domains/bookingWorkflow.ts`

Fully refactored from base44's original fragmented booking system. Unified across website and portal.

What it handles internally:
- Availability validation
- Soft hold → confirm flow
- Automation task queuing
- Notification scheduling

Related entities: `Booking`, `Room`, `Client`, `Invoice`, `BookingAccessWindow`, `CreditTransaction`

Key edge functions: `manageSoftHold`, `processBookingLifecycle`, `syncBookingToGoogleCalendar`, `requestBookingExtension`

**Do not modify booking core logic without coordinating with the booking chat.**

---

### Invoice Engine ✅

**Location:** `@/lib/domains/invoiceEngine.ts`

All invoice operations are centralized here. Never write inline invoice logic anywhere else.

| Function | Purpose |
|---|---|
| `generateInvoice(bookingId)` | Create invoice from booking |
| `sendInvoice(invoiceId)` | Email invoice to client |
| `markInvoicePaid(invoiceId, options)` | Record payment |
| `voidInvoice(invoiceId)` | Cancel an invoice |
| `uploadInvoiceReceipt(invoiceId, url)` | Attach receipt document |
| `getInvoiceForBooking(bookingId)` | Fetch invoice by booking |
| `getInvoicesByClientEmail(email)` | Fetch all invoices for a client |
| `updateInvoiceDetails(invoiceId, fields)` | Update metadata fields |

---

### Pricing Engine ✅

**Location:** `@/lib/domains/pricingEngine.ts`

All price arithmetic lives here. No inline math for hourly rates, credit costs, day rates, deposits, or discounts anywhere in pages or components.

---

### Notification Engine ✅

**Frontend types:** `@/lib/domains/notificationEngine.ts`
**Email delivery:** `supabase/functions/_shared/notificationEngine.ts` (Deno, Resend-backed)

Notification types: `booking_confirmed`, `session_reminder_24h`, `session_reminder_1h`, `booking_cancelled`

Notifications are queued by `bookingAutomation.ts` task queue and delivered by the edge function worker. Never add direct email sending to pages or components.

---

### Auth System ✅

- **Portal:** Supabase exclusively in all environments (no localAuth)
- **Website:** Supabase in all hosted environments; `localAuth` available in local dev via `VITE_USE_LOCAL_AUTH`
- **Super admin:** `levi@48labs.studio`
- **Local Supabase project:** `bqyddkagszndrgmtwvmx`
- **Production Supabase project:** `evictatnjhiqyuvdozbu`

Never add custom auth logic, session storage hacks, or new `VITE_USE_LOCAL_AUTH` references.

---

### Domain Layer ✅

**Location:** `@/lib/domains/`

All data access abstracted into domain modules. Zero `api.entities.*` calls remain in either portal or website (8 edge function `api.functions.invoke()` calls intentionally preserved — see below).

| Module | Entities |
|---|---|
| `pricing` | Room, AddOn, GlobalAddOn, Service, MembershipPlan, CreditBundle, CreditPackage, CreditConfiguration, CreditPricingTier, PricingSettings, PricingItem, RoomPricing |
| `clients` | Client, ClientComplianceRecord, ClientSubscription, CreditTransaction, StripeCustomer, ClientPIN |
| `users` | User, UserProfile, AdminRole, Invite |
| `bookings` | Booking, BookingAccessWindow, BookingExtensionRequest, BookingGuestList, BookingNotification, Invoice, OperatingHours |
| `system` | AppSetting, SharedCalendarToken, Notification, MarketingMedia, HeroSettings, Expense, EmailCampaign, ImageCropHistory |
| `access-control` | LockIntegration, RoomLockMapping, OperatingHours, iPadSession, iPadCommand, SyncReviewItem, SyncState |

---

### Design Token System ✅

`[data-theme="dark"|"light"]` on `<html>` activates the CSS custom property set. Semantic Tailwind aliases (`bg-canvas`, `bg-surface`, `bg-elevated`, etc.) are defined in both repos' `tailwind.config.js`.

See `CLAUDE_STANDARDS.md` Section 2–3 for the full token table.

---

### Portal Primitive Components ✅

All live in `48labs-portal/src/components/ui/`:

`PortalTable`, `PortalDrawer`, `PageShell`, `SectionCard`, `SettingCard`, `TabBar`, `FilterPills`, `SearchInput`, `SegmentedControl`, `Spinner`, `EmptyState`, `FloatingPanel`

See `CLAUDE_STANDARDS.md` Section 4 for usage examples.

---

## 3. Recent Refactors (Phase 1 — 2026-04-21)

| Item | What changed |
|---|---|
| `48labs-website/index.html` | Added `data-theme="dark"` — CRITICAL: without this all CSS vars resolved to undefined |
| `48labs-website/src/index.css` | Added `--interactive-hover`; updated `--panel-elevated` dark → `#243347` |
| `48labs-website/tailwind.config.js` | Added full semantic alias layer (canvas, surface, elevated, on-surface-*, border-*, interactive) |
| 81 website files | `slate-*` → semantic tokens (bg, text, border, hover, gradient, placeholder) |
| 13 website files | `api.entities.*` → direct domain imports from `@/lib/domains/*` |
| 9 portal files | Gradient `slate-*` → semantic tokens |
| `MonthCalendar.jsx` (portal) | Tooltip arrow `border-t-slate-700` → `border-t-border-soft` |
| `BookingFlow.jsx` (portal) | `bg-white` headers → `bg-canvas` |
| `MarketingHeader.jsx` (website) | `api.entities.AppSetting` → `getAppSettingByKey()`; all slate tokens removed |
| `MarketingFooter.jsx` (website) | Same fixes as MarketingHeader |
| `button.jsx` (website) | `outline` variant: slate tokens → semantic tokens (now matches portal exactly) |

---

## 4. Deprecated Patterns — Do Not Use

| Pattern | Replacement |
|---|---|
| `import { data as api } from '@/lib/data'` then `api.entities.*` | Direct domain imports from `@/lib/domains/*` |
| `bg-slate-950/900/800/700/600` on surfaces | `bg-canvas`, `bg-surface`, `bg-elevated` |
| `text-slate-200/300/400/500` | `text-on-surface`, `text-on-surface-secondary`, `text-on-surface-muted` |
| `border-slate-700/800/900` | `border-border-soft` |
| `border-slate-500/600` | `border-border-hard` |
| `hover:bg-slate-700/800` | `hover:bg-interactive` |
| `placeholder-slate-*` (Tailwind v2) | `placeholder:text-on-surface-muted` |
| `text-white` in non-button contexts | `text-on-surface` |
| Custom booking creation flows | `createBookingWorkflow()` |
| Inline invoice logic | `invoiceEngine.ts` functions |
| Inline price math | `pricingEngine.ts` |
| Custom table built from `<table>` | `<PortalTable>` |
| Custom slide-in panels | `<PortalDrawer>` |
| Raw `supabase.from()` in pages/components | `@/lib/domains/*` |
| `VITE_USE_LOCAL_AUTH` in new code | Never add new references |

---

## 5. Deferred Items (Documented, Not Bugs)

| Item | Detail | When to address |
|---|---|---|
| Portal `--panel-elevated` dark | Still `#1E293B` (same as `--panel-bg`); website leads at `#243347` | When confirmed with user |
| `api.functions.invoke()` in 8 website files | Edge functions with no domain wrapper: `processUnifiedPurchase`, `googleCalendarManager`, `getRoomAvailability`, `submitTourRequest`, `submitContactForm`, `createMembershipAccount` | When edge functions get domain layer |
| Status color aliases in website | Portal has them; website doesn't use booking-status pills | Add when status UI appears in website |
| `bookingAutomation.ts` raw `supabase.rpc()` | One known call that should move into `operations.ts` | Future cleanup |
| Booking Engine sync to `48labs-design` | Design repo still has base44's original fragmented version | Phase 3 |
| Base44 Superagent | Not yet configured | Phase 2 Task 4 |
| `48labs-sync` git push | Files exist locally, not yet pushed to `github.com/Cinedex/48labs-sync` | Immediate |

---

## 6. Build Status

| Repo | Status | Notes |
|---|---|---|
| `48labs-website` | ✅ Clean (exit 0) | Verified 2026-04-21 after Phase 1 |
| `48labs-portal` | ✅ Clean (exit 0) | Pre-existing Vite chunking warnings only — not introduced by Phase 1 |

---

## 7. Stack Reference

| Layer | Technology |
|---|---|
| Frontend | React |
| Styling | Tailwind CSS + shadcn/ui |
| Language | TypeScript / JSX |
| State / Data | TanStack React Query |
| Routing | React Router DOM |
| Animations | Framer Motion |
| Icons | Lucide React |
| Backend | Deno serverless (base44 functions) |
| Auth | Supabase (all hosted) / localAuth (website local dev) |
| Database | Supabase (Postgres) with RLS |
| Payments | Stripe |
| Deployment | Cloudflare Pages |
| Calendar | Google Calendar API |
| Email | Resend |
