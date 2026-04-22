# 48Labs — Split Rules
> Last updated: 2026-04-22
> Defines what belongs in `48labs-website`, `48labs-portal`, or both.
> Claude Code uses this when deciding where to migrate base44 output.
> Base44 reads this to understand which repo a new feature targets.

---

## Rule 1 — Website (`48labs-website`)

Features that go to the website if they are:
- Public-facing marketing or informational content
- Accessible without authentication
- Part of the guest booking or purchase flow
- SEO-relevant pages

### Website-only pages and components

| Pattern | Examples |
|---|---|
| Public marketing pages | `Landing.jsx`, `About.jsx`, `FAQ.jsx`, `Roadmap.jsx`, `Contact.jsx` |
| Studio discovery | `Studios.jsx`, `RoomProfile.jsx`, `Services.jsx` |
| Guest booking flow | `GuestBooking.jsx`, `GuestBuyCredits.jsx`, `UnifiedCheckout.jsx` |
| Public auth entry | `Register.jsx`, `MembershipSignup.jsx` |
| Dynamic public pricing | `DynamicCreditsPage.jsx`, `DynamicMembershipsPage.jsx` |
| Marketing components | `MarketingHeader.jsx`, `MarketingFooter.jsx`, `StudioTourCTA.jsx`, `RoomOperatingHoursDisplay.jsx` |
| Payment outcomes | `PaymentSuccess.jsx`, `PaymentCancel.jsx`, `CheckoutPaymentSuccess.jsx` |

---

## Rule 2 — Portal (`48labs-portal`)

Features that go to the portal if they are:
- Behind authentication (admin or client)
- Admin management interfaces
- Client self-service (bookings, invoices, profile)
- iPad/kiosk interfaces
- Internal operational tooling

### Portal-only pages and components

| Pattern | Examples |
|---|---|
| Admin pages | All `Admin*.jsx` pages (dashboard, rooms, clients, pricing, settings…) |
| Client portal pages | All `Client*.jsx` pages (dashboard, bookings, invoices, profile) |
| Booking management | `BookingFlow.jsx`, `BookingDetailDrawer.jsx` |
| iPad / studio kiosk | All `src/components/ipad/*`, `StudioController.jsx`, `AdminiPadController.jsx` |
| Portal layout | `AdminLayout.jsx`, `ClientPortalLayout.jsx`, `Sidebar.jsx`, `PortalTopBar.jsx` |
| Portal primitives | `PortalTable`, `PortalDrawer`, `PageShell`, `SectionCard`, `SettingCard`, `TabBar`, `FilterPills`, `SearchInput`, `SegmentedControl`, `Spinner`, `EmptyState`, `FloatingPanel` |
| Dashboard components | `MonthCalendar.jsx`, `DashboardMetricCard.jsx`, `SessionTimelineCard.jsx` |
| Financial | `AdminFinancialDashboard.jsx`, all `src/components/financial/*` |

---

## Rule 3 — Both repos

Features that live in both if they are:
- Domain / data layer (no UI)
- Auth infrastructure
- Shared edge functions
- Config / environment files

### Both repos

| Layer | Location in each repo | Notes |
|---|---|---|
| Domain modules | `src/lib/domains/*` | Identical — copy verbatim |
| Supabase client | `src/lib/supabaseClient.ts` | Identical |
| Auth context | `src/lib/AuthContext.jsx` | Identical |
| Auth routes helper | `src/lib/authRoutes.ts` | Identical |
| Pricing engine | `src/lib/domains/pricingEngine.ts` | Identical |
| Booking workflow | `src/lib/domains/bookingWorkflow.ts` | Identical |
| Invoice engine | `src/lib/domains/invoiceEngine.ts` | Identical |
| Tailwind config (token aliases) | `tailwind.config.js` | Portal has status colors; website does not |
| shadcn/ui base components | `src/components/ui/{button,input,select,dialog…}` | Identical |

---

## Rule 4 — Design only (never migrate directly)

Files that exist only in `48labs-design` and are base44 prototypes, not production targets:

- `src/database/*` — migration planning artifacts (informational, not deployed)
- `src/contracts/*` — schema contracts (informational)
- `base44/entities/*.jsonc` — base44 entity definitions (not deployable)
- `base44/functions/*/entry.ts` — base44 edge function stubs (use Deno equivalents in `supabase/functions/`)
- `src/lib/workflow-data.js` — base44 workflow visualization data
- `src/pages/AdminWorkflowMap.jsx` — internal planning UI, not production

---

## Decision checklist

When base44 builds something new, ask:

1. **Is the user logged in to access it?**
   - No → website
   - Yes, as admin → portal
   - Yes, as client → portal

2. **Is it a page, component, or domain module?**
   - Page or component → apply rules 1 or 2 above
   - Domain module, auth, or config → both repos

3. **Does it appear in `48labs-design/src/components/ui/`?**
   - If it matches a name in `canonical_component_names` in `manifest.json` → Claude Code already owns it, do not rebuild

4. **Is it in `claude_code_owns` in `manifest.json`?**
   - Yes → Claude Code owns the refined version; base44 should not modify the `48labs-design` source
