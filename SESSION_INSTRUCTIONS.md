# 48Labs — Base44 Session Instructions

> **Fetch this file at the start of every Base44 session.**
> Raw URL: `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/SESSION_INSTRUCTIONS.md`
> Last updated: 2026-04-21

This file tells you what already exists, what patterns to follow, and what never to rebuild.
Read it before generating any new UI, any new data fetching logic, or any new component.

---

## 1. What Already Exists — Do Not Rebuild

These systems are fully implemented and owned by Claude Code. Building replacements or variations will create drift that must be manually resolved.

### Booking Engine

**Entry point:** `createBookingWorkflow(input)` in `@/lib/domains/bookingWorkflow.ts`

Never create a custom booking creation flow. Always call `createBookingWorkflow()`. It handles:
- Availability validation
- Soft hold → confirm
- Automation task queuing
- Notification scheduling

**Availability:** `getRoomAvailability({ date, roomId, durationHours })` in `@/lib/domains/bookings.ts`

### Invoice Engine

**Location:** `@/lib/domains/invoiceEngine.ts`

Functions: `generateInvoice(bookingId)`, `sendInvoice(invoiceId)`, `markInvoicePaid(invoiceId, options)`, `voidInvoice(invoiceId)`, `uploadInvoiceReceipt(invoiceId, url)`, `getInvoiceForBooking(bookingId)`, `getInvoicesByClientEmail(email)`, `updateInvoiceDetails(invoiceId, fields)`

Never write inline invoice logic. Never call `data.functions.invoke('generateInvoice', ...)` — the engine exists.

### Pricing Engine

**Location:** `@/lib/domains/pricingEngine.ts`

All price math lives here. No inline arithmetic for hourly rates, credit costs, day rates, deposits, or discounts anywhere in pages or components.

### Notification Engine

**Frontend types:** `@/lib/domains/notificationEngine.ts`
**Email delivery:** `supabase/functions/_shared/notificationEngine.ts` (Deno, Resend-backed)

Notification types: `booking_confirmed`, `session_reminder_24h`, `session_reminder_1h`, `booking_cancelled`

Notifications are queued via `bookingAutomation.ts` task queue and delivered by the edge function worker. Do not add direct email sending to pages or components.

### Auth System

Supabase auth in all hosted environments. Portal: Supabase exclusively. Website: Supabase in all hosted envs.

Never add custom auth logic, never add session storage hacks, never add `VITE_USE_LOCAL_AUTH` references to new code.

### Domain Layer

All data access goes through `@/lib/domains/*`. See Section 3 for the full entity map and import pattern.

---

## 2. Sync Layer Files — Read These Too

| File | URL | Purpose |
|---|---|---|
| `SESSION_INSTRUCTIONS.md` | `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/SESSION_INSTRUCTIONS.md` | This file |
| `CLAUDE_STANDARDS.md` | `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/CLAUDE_STANDARDS.md` | Full token reference, component patterns, naming rules |
| `PROJECT_STATE.md` | `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/PROJECT_STATE.md` | All major systems, recent refactors, deprecated items |
| `drift-log.md` | `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/drift-log.md` | What you built that Claude hasn't integrated, and vice versa |
| `manifest.json` | `https://raw.githubusercontent.com/Cinedex/48labs-sync/main/manifest.json` | Every component/feature mapped to website, portal, or both |

---

## 3. Data Layer — Import Pattern

### Always: Direct Domain Imports

```js
// CORRECT
import { Room, CreditBundle, MembershipPlan } from '@/lib/domains/pricing';
import { Client } from '@/lib/domains/clients';
import { Booking, Invoice } from '@/lib/domains/bookings';
import { AppSetting, MarketingMedia } from '@/lib/domains/system';
import { User, Invite } from '@/lib/domains/users';
```

### Never: Data Facade

```js
// WRONG — this pattern is deprecated and will be removed
import { data as api } from '@/lib/data';
api.entities.Room.list()        // ❌
api.entities.Client.filter()    // ❌
data.entities.Booking.get()     // ❌
```

### Entity → Domain Module Map

| Entity | Import from |
|---|---|
| Room, AddOn, GlobalAddOn, Service, MembershipPlan, CreditBundle, CreditPackage, CreditConfiguration, CreditPricingTier, PricingSettings, PricingItem, RoomPricing | `@/lib/domains/pricing` |
| Client, ClientComplianceRecord, ClientSubscription, CreditTransaction, StripeCustomer, ClientPIN | `@/lib/domains/clients` |
| User, UserProfile, AdminRole, Invite | `@/lib/domains/users` |
| Booking, BookingAccessWindow, BookingExtensionRequest, BookingGuestList, BookingNotification, Invoice, OperatingHours | `@/lib/domains/bookings` |
| AppSetting, SharedCalendarToken, Notification, MarketingMedia, HeroSettings, Expense, EmailCampaign, ImageCropHistory | `@/lib/domains/system` |
| LockIntegration, RoomLockMapping, OperatingHours, iPadSession, iPadCommand, SyncReviewItem, SyncState | `@/lib/domains/access-control` |

### Edge Functions — Still OK to Invoke

These 6 functions have no domain wrapper yet. `api.functions.invoke()` is acceptable for these only:

| Function | Used for |
|---|---|
| `getRoomAvailability` | Availability slots from edge function |
| `googleCalendarManager` | Google Calendar sync |
| `processUnifiedPurchase` | Checkout / payment processing |
| `submitTourRequest` | Studio tour form submission |
| `createMembershipAccount` | Membership signup |
| `submitContactForm` | Contact form submission |

---

## 4. Design Tokens — What to Use

The token system is `[data-theme="dark"]` on `<html>` (website) or toggled per session (portal). All surfaces must use semantic Tailwind classes — never hardcoded Tailwind slate/gray/white colors.

### Surface Backgrounds

| Use case | Class |
|---|---|
| Page background | `bg-canvas` |
| Panel / card | `bg-surface` |
| Elevated element (input, inner card) | `bg-elevated` |

### Text

| Use case | Class |
|---|---|
| Primary content | `text-on-surface` |
| Secondary / labels | `text-on-surface-secondary` |
| Hints / placeholder / captions | `text-on-surface-muted` |

### Borders

| Use case | Class |
|---|---|
| Card, panel, section border | `border-border-soft` |
| Input, strong separator | `border-border-hard` |

### Interactive States

| Use case | Class |
|---|---|
| Hover background on ghost/outline buttons | `hover:bg-interactive` |

### What Not to Use on Surfaces

```
❌ bg-slate-950  bg-slate-900  bg-slate-800  bg-slate-700
❌ text-slate-100  text-slate-200  text-slate-300  text-slate-400  text-slate-500
❌ border-slate-700  border-slate-800  border-slate-900
❌ text-white  (use text-on-surface instead)
❌ bg-white   (use bg-canvas or bg-surface instead)
❌ hover:bg-slate-700  hover:bg-slate-800
```

**Exception:** `text-white` is correct on buttons with colored backgrounds (`bg-blue-600 text-white`). `text-white/xx` opacity variants are acceptable on intentionally dark-pinned pages (Landing, GuestBooking) for layered luminance effects.

---

## 5. Component Primitives — Use These, Don't Rebuild Them

These live in `src/components/ui/` (portal). Use them before creating new layout or table components.

### `PortalTable`
Sortable, keyboard-accessible data table.
```jsx
<PortalTable
  columns={[{ id, label, render: (row) => <node /> }]}
  data={rows}
  rowKey="id"
  rowActions={(row) => <buttons />}
  emptyMessage="No items found."
  emptyIcon={SomeLucideIcon}
/>
```

### `PortalDrawer`
Slide-in panel. Escape/backdrop to close. Body scroll lock.
```jsx
<PortalDrawer open={open} onClose={onClose} title="Edit Item" width="max-w-xl">
  {children}
</PortalDrawer>
```

### `SectionCard`
Titled content block.
```jsx
<SectionCard title="Settings" subtitle="Configure..." actions={<Button />}>
  {children}
</SectionCard>
```

### `PageShell`
Page layout wrapper.
```jsx
<PageShell maxWidth="6xl">
  {children}
</PageShell>
```

### `TabBar`
```jsx
<TabBar
  tabs={[{ value: 'all', label: 'All' }, { value: 'active', label: 'Active' }]}
  active={activeTab}
  onChange={setActiveTab}
/>
```

### `FilterPills`
```jsx
<FilterPills
  filters={[{ id: 'all', label: 'All', count: 42 }]}
  active={activeFilter}
  onChange={setActiveFilter}
/>
```

### `SearchInput`
```jsx
<SearchInput value={q} onChange={setQ} placeholder="Search…" />
```

### `SegmentedControl`
```jsx
<SegmentedControl
  options={[{ value: 'list', label: 'List' }, { value: 'grid', label: 'Grid' }]}
  value={view}
  onChange={setView}
/>
```

### `Spinner`
```jsx
<Spinner center />          // centered in parent
<Spinner size="sm" />       // sm | md | lg
```

### `EmptyState`
```jsx
<EmptyState
  icon={FileText}
  title="No invoices yet"
  description="Create your first invoice to get started."
  action={{ label: 'New Invoice', onClick: handleNew }}
/>
```

### `SettingCard`
For settings panels:
```jsx
<SettingCard title="Notifications" description="Configure email alerts" icon={Bell}>
  {children}
</SettingCard>
```

---

## 6. Naming Conventions

### Files
- Pages: `Admin*.jsx`, `Client*.jsx`, `Guest*.jsx`, or PascalCase for public pages
- Components: `PascalCase.jsx`
- Domain modules: `camelCase.ts` (never `.tsx`)
- Hooks: `useCamelCase.js`

### Domain Helper Functions
Verb-first, camelCase:
- `getX()` — fetch single item
- `listX()` — fetch collection
- `saveX()` — create or update
- `deleteX()` — remove
- `validateX()` — check validity
- `markX()` — update a status flag
- `queueX()` — schedule async work
- `deriveX()` — compute from existing data
- `normalizeX()` — transform input shape

### Components
- Props: camelCase
- Event handlers: `onX` prefix (`onClose`, `onChange`, `onSubmit`)
- Boolean props: `isX` or adjective (`center`, `elevated`, `hoverable`)

---

## 7. Architecture Rules

1. **No inline domain logic in pages or components.** All data operations through `@/lib/domains/*`.
2. **No inline price math anywhere.** Only `pricingEngine.ts`.
3. **No direct `supabase.*` calls** outside `src/lib/supabaseClient.ts`, `src/lib/domains/*`, and `supabase.auth.*`. Exception: `bookingAutomation.ts` has one known raw `supabase.rpc()` call pending cleanup.
4. **No bypassing `createBookingWorkflow()`.** All booking creation goes through it.
5. **Booking system internals are owned by a separate Claude chat.** Do not modify booking core logic unless explicitly coordinated.
6. **Supabase RLS is live on all core tables.** Do not relax policies.
7. **Admin pages use `AdminPageWrapper` + `PortalTopBar`.** Do not create standalone page layouts.

---

## 8. What the Repos Are For

| Repo | Purpose | Who writes |
|---|---|---|
| `48labs-design` | Fast UI/UX prototyping. Raw, unstructured. | Base44 |
| `48labs-sync` | Sync brain. Tracks state, rules, drift. No UI code. | Claude Code |
| `48labs-website` | Clean marketing site (`48labs.studio`) | Claude Code |
| `48labs-portal` | Clean admin/client portal (`portal.48labs.studio`) | Claude Code |

Base44 builds in `48labs-design`. Claude Code reviews, cleans, and migrates into `48labs-website` and `48labs-portal`. Never treat `48labs-design` as the deployment target.

---

## 9. When You Build Something New

Before generating new UI in `48labs-design`:

1. Check this file — does it already exist?
2. Check `PROJECT_STATE.md` — is it in the deprecated list?
3. Check `manifest.json` — is it mapped to a Claude-owned file?
4. If yes to any: reference what exists, don't rebuild it.
5. If no: build freely in `48labs-design`. Claude Code will integrate it in the next session.

---

## 10. Quick Reference — Most Common Mistakes

| Mistake | Correct approach |
|---|---|
| Using `api.entities.Room.list()` | `import { Room } from '@/lib/domains/pricing'` then `Room.list()` |
| Writing price calculation inline | Import and call `pricingEngine.ts` |
| Creating a new booking flow | Call `createBookingWorkflow(input)` |
| Using `bg-slate-900` on a surface | Use `bg-canvas` |
| Using `text-slate-400` | Use `text-on-surface-muted` |
| Using `border-slate-700` | Use `border-border-soft` |
| Building a new data table from scratch | Use `<PortalTable>` |
| Building a new slide-in panel | Use `<PortalDrawer>` |
| Direct `supabase.from()` in a page | Go through `@/lib/domains/*` |
