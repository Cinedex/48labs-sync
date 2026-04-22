# 48Labs — Claude Code Standards
> Last updated: 2026-04-21
> This file is the authoritative reference for design tokens, component patterns, and naming conventions.
> Base44 reads this via raw URL. Claude Code updates it after any token or pattern change.

---

## 1. Design Token System

### How It Works

Tokens are CSS custom properties defined on the `[data-theme]` attribute of `<html>`. Both light and dark sets are declared — the correct set activates based on whichever theme string is on the element.

```html
<!-- Website: permanently dark -->
<html lang="en" data-theme="dark">

<!-- Portal: togglable per user session -->
<html data-theme="dark">   <!-- or data-theme="light" -->
```

The Tailwind alias layer maps semantic class names to these CSS vars. **Always use the alias classes — never reference the raw CSS var names in JSX.**

---

## 2. CSS Custom Properties — Full Reference

### Surface / Background vars

| CSS var | Light | Dark (portal) | Dark (website) |
|---|---|---|---|
| `--bg-primary` | `#F1F5F9` | `#0F172A` | `#0F172A` |
| `--panel-bg` | `#E2E8F0` | `#1E293B` | `#1E293B` |
| `--panel-elevated` | `#FFFFFF` | `#1E293B` | `#243347` |
| `--element-bg` | `#CBD5E1` | `#334155` | `#334155` |

> Note: Website `--panel-elevated` dark is `#243347` (visually distinct from `--panel-bg`). Portal is still `#1E293B` — update pending.

### Text vars

| CSS var | Light | Dark |
|---|---|---|
| `--text-primary` | `#0F172A` | `#F1F5F9` |
| `--text-secondary` | `#334155` | `#CBD5E1` |
| `--text-muted` | `#64748B` | `#94A3B8` |

### Border vars

| CSS var | Light | Dark |
|---|---|---|
| `--border-subtle` | `#CBD5E1` | `rgba(255,255,255,0.08)` |
| `--border-strong` | `#94A3B8` | `rgba(255,255,255,0.15)` |

### Interactive

| CSS var | Light | Dark |
|---|---|---|
| `--interactive-hover` | `rgba(0,0,0,0.06)` | `rgba(255,255,255,0.08)` |

### Status colors (portal only — not on website)

| CSS var | Light bg | Light text | Dark bg | Dark text |
|---|---|---|---|---|
| `--status-pending-*` | `#FEF3C7` | `#92400E` | `rgba(251,191,36,0.15)` | `#FBBF24` |
| `--status-confirmed-*` | `#DCFCE7` | `#166534` | `rgba(34,197,94,0.15)` | `#4ADE80` |
| `--status-cancelled-*` | `#FEE2E2` | `#991B1B` | `rgba(239,68,68,0.15)` | `#F87171` |
| `--status-active-*` | `#EDE9FE` | `#5B21B6` | `rgba(168,85,247,0.15)` | `#C084FC` |

---

## 3. Tailwind Semantic Alias Layer — Use These

### What exists in both portal and website

| Class | Resolves to | Usage |
|---|---|---|
| `bg-canvas` | `--bg-primary` | Page background |
| `bg-surface` | `--panel-bg` | Card / panel |
| `bg-elevated` | `--panel-elevated` | Input field, inner card |
| `text-on-surface` | `--text-primary` | Body text, headings |
| `text-on-surface-secondary` | `--text-secondary` | Labels, nav links |
| `text-on-surface-muted` | `--text-muted` | Captions, hints, placeholders |
| `border-border-soft` | `--border-subtle` | Card, panel, section borders |
| `border-border-hard` | `--border-strong` | Input fields, strong separators |
| `bg-interactive` | `--interactive-hover` | Hover state on ghost/outline elements |

### What exists in portal only (not website)

| Class | Resolves to | Usage |
|---|---|---|
| `bg-status-pending` | `--status-pending-bg` | Pending badge background |
| `text-status-pending-text` | `--status-pending-text` | Pending badge text |
| `bg-status-confirmed` | `--status-confirmed-bg` | Confirmed badge background |
| `text-status-confirmed-text` | `--status-confirmed-text` | Confirmed badge text |
| `bg-status-cancelled` | `--status-cancelled-bg` | Cancelled badge background |
| `text-status-cancelled-text` | `--status-cancelled-text` | Cancelled badge text |
| `bg-status-active` | `--status-active-bg` | Active/credit badge background |
| `text-status-active-text` | `--status-active-text` | Active/credit badge text |

### What NOT to use on surfaces

```
❌  bg-slate-950  bg-slate-900  bg-slate-800  bg-slate-700  bg-slate-600
❌  text-slate-100  text-slate-200  text-slate-300  text-slate-400  text-slate-500
❌  border-slate-700  border-slate-800  border-slate-900
❌  text-white       (use text-on-surface)
❌  bg-white         (use bg-canvas or bg-surface)
❌  hover:bg-slate-700  hover:bg-slate-800
```

**Allowed exceptions:**
- `text-white` on buttons with colored backgrounds (`bg-blue-600 text-white` — correct)
- `text-white/xx` opacity variants on forced-dark pages (`Landing.jsx`, `GuestBooking.jsx`) — intentional luminance-layering; no token equivalent exists
- `bg-white/[0.0x]` alpha overlays on intentionally dark-pinned pages
- Decorative whites: toggle thumbs, document preview backgrounds, signature image containers

---

## 4. Component Patterns

### Button

File: `src/components/ui/button.jsx` (identical in both repos)

```jsx
import { Button } from '@/components/ui/button';

// Primary action — use for main CTAs
<Button>Save</Button>

// With colored background — CTA style (keep text-white here)
<Button className="bg-blue-600 hover:bg-blue-700 text-white">Book a Session</Button>

// Outline — secondary action
<Button variant="outline">Cancel</Button>

// Ghost — tertiary / nav actions
<Button variant="ghost">View Details</Button>

// Destructive
<Button variant="destructive">Delete</Button>

// Sizes: default (h-9) | sm (h-8) | lg (h-10) | icon (h-9 w-9)
<Button size="sm">Small</Button>
<Button size="icon"><PlusIcon /></Button>
```

**Never** recreate button styling inline. **Never** use `bg-slate-*` as a button background.

---

### PortalTable (portal only)

File: `src/components/ui/PortalTable.jsx`

Sortable, keyboard-accessible data table with built-in empty state.

```jsx
import PortalTable from '@/components/ui/PortalTable';

<PortalTable
  columns={[
    { id: 'name', label: 'Name', render: (row) => <span>{row.name}</span> },
    { id: 'status', label: 'Status', render: (row) => <StatusBadge status={row.status} /> },
  ]}
  data={rows}
  rowKey="id"
  rowActions={(row) => (
    <>
      <Button size="sm" onClick={() => handleEdit(row)}>Edit</Button>
    </>
  )}
  onRowClick={(row) => navigate(`/bookings/${row.id}`)}
  emptyMessage="No bookings found."
  emptyIcon={CalendarIcon}
  hoverable      // default true — remove to suppress row hover
/>
```

Do **not** build a custom table from `<table>` elements when this component fits.

---

### PortalDrawer (portal only)

File: `src/components/ui/PortalDrawer.jsx`

Slide-in side panel. Escape key and backdrop click to close. Body scroll locked while open.

```jsx
import PortalDrawer from '@/components/ui/PortalDrawer';

<PortalDrawer open={open} onClose={() => setOpen(false)} title="Edit Client" width="max-w-xl">
  <div className="space-y-4">
    {/* form fields */}
  </div>
</PortalDrawer>
```

Width options: `max-w-sm`, `max-w-md`, `max-w-xl`, `max-w-2xl`. Default is `max-w-xl`.

Do **not** use Sheet or Dialog from shadcn as a slide-in panel substitute when PortalDrawer fits.

---

### SectionCard (portal only)

File: `src/components/ui/SectionCard.jsx`

Standard section/card container. Uses `bg-surface` (or `bg-elevated` with prop) + `border-border-soft` + `rounded-xl`.

```jsx
import SectionCard from '@/components/ui/SectionCard';

// Standard
<SectionCard title="Billing" subtitle="Manage payment methods">
  {children}
</SectionCard>

// With header action
<SectionCard title="Team Members" actions={<Button size="sm">Invite</Button>}>
  {children}
</SectionCard>

// Edge-to-edge content (table inside card)
<SectionCard title="Bookings" noPadding>
  <PortalTable ... />
</SectionCard>

// Elevated surface
<SectionCard elevated>
  {children}
</SectionCard>
```

Props: `title`, `subtitle`, `actions`, `noPadding`, `elevated`, `className`.

---

### PageShell (portal only)

File: `src/components/ui/PageShell.jsx`

Page layout wrapper. Centers content, applies max-width, vertical padding.

```jsx
import PageShell from '@/components/ui/PageShell';

<PageShell maxWidth="6xl">
  {children}
</PageShell>
```

Max-width options match Tailwind: `4xl`, `5xl`, `6xl`, `7xl`. Default: `6xl`.

---

### TabBar (portal only)

File: `src/components/ui/TabBar.jsx`

Horizontal tab navigation.

```jsx
import TabBar from '@/components/ui/TabBar';

<TabBar
  tabs={[
    { value: 'all', label: 'All' },
    { value: 'active', label: 'Active' },
    { value: 'archived', label: 'Archived' },
  ]}
  active={activeTab}
  onChange={setActiveTab}
/>
```

---

### FilterPills (portal only)

File: `src/components/ui/FilterPills.jsx`

Horizontal filter chips with optional counts.

```jsx
import FilterPills from '@/components/ui/FilterPills';

<FilterPills
  filters={[
    { id: 'all', label: 'All', count: 42 },
    { id: 'pending', label: 'Pending', count: 7 },
    { id: 'confirmed', label: 'Confirmed', count: 35 },
  ]}
  active={activeFilter}
  onChange={setActiveFilter}
/>
```

---

### SearchInput (portal only)

File: `src/components/ui/SearchInput.jsx`

Debounced search field with icon.

```jsx
import SearchInput from '@/components/ui/SearchInput';

<SearchInput value={query} onChange={setQuery} placeholder="Search clients…" />
```

---

### SegmentedControl (portal only)

File: `src/components/ui/SegmentedControl.jsx`

Toggle between 2–4 mutually exclusive views (list/grid, week/month, etc.).

```jsx
import SegmentedControl from '@/components/ui/SegmentedControl';

<SegmentedControl
  options={[
    { value: 'list', label: 'List' },
    { value: 'grid', label: 'Grid' },
  ]}
  value={view}
  onChange={setView}
/>
```

---

### Spinner

File: `src/components/ui/Spinner.jsx`

```jsx
import Spinner from '@/components/ui/Spinner';

<Spinner center />          // centered in containing block
<Spinner size="sm" />       // sm | md | lg
<Spinner />                 // default size, inline
```

---

### EmptyState

File: `src/components/ui/EmptyState.jsx`

```jsx
import EmptyState from '@/components/ui/EmptyState';
import { FileText } from 'lucide-react';

<EmptyState
  icon={FileText}
  title="No invoices yet"
  description="Create your first invoice to get started."
  action={{ label: 'New Invoice', onClick: handleNew }}
/>
```

Props: `icon` (Lucide component), `title`, `description`, `action` ({ label, onClick }).

---

### SettingCard (portal only)

File: `src/components/ui/SettingCard.jsx`

For settings screens — icon + title + description with children content.

```jsx
import SettingCard from '@/components/ui/SettingCard';
import { Bell } from 'lucide-react';

<SettingCard title="Notifications" description="Configure email alerts" icon={Bell}>
  <Switch ... />
</SettingCard>
```

---

### FloatingPanel (portal only)

File: `src/components/ui/FloatingPanel.jsx`

Floating overlay panel for contextual actions (not a modal, not a drawer — a floating card).

```jsx
import FloatingPanel from '@/components/ui/FloatingPanel';

<FloatingPanel open={open} onClose={onClose} anchor={anchorRef}>
  {children}
</FloatingPanel>
```

---

## 5. Naming Conventions

### Files

| Type | Convention | Example |
|---|---|---|
| Admin portal page | `Admin*.jsx` | `AdminClientsPage.jsx` |
| Client portal page | `Client*.jsx` | `ClientDashboard.jsx` |
| Guest / public page | `Guest*.jsx` | `GuestBooking.jsx` |
| Other public page | PascalCase | `Landing.jsx`, `Studios.jsx` |
| Shared component | PascalCase | `RoomCard.jsx`, `MonthCalendar.jsx` |
| Domain module | camelCase `.ts` | `bookings.ts`, `pricingEngine.ts` |
| Hook | `use` prefix | `useBookingState.js` |
| Edge function | camelCase | `generateInvoice.ts` |

**Domain modules are always `.ts` — never `.tsx`.** They never render JSX.

### Domain Helper Functions

Always verb-first, camelCase:

| Verb | Meaning |
|---|---|
| `getX()` | Fetch a single item |
| `listX()` | Fetch a collection |
| `saveX()` | Create or update |
| `deleteX()` | Remove |
| `validateX()` | Check validity, return boolean or error |
| `markX()` | Update a status flag |
| `queueX()` | Schedule async work |
| `deriveX()` | Compute from existing data (no I/O) |
| `normalizeX()` | Transform input shape |

### Component Props

| Convention | Examples |
|---|---|
| camelCase | `roomId`, `onClose`, `isLoading` |
| Event handlers: `on` prefix | `onClose`, `onChange`, `onSubmit`, `onDelete` |
| Boolean props: `is` or adjective | `isLoading`, `center`, `elevated`, `hoverable`, `noPadding` |

---

## 6. Data Layer Rules

### Import Pattern

```js
// CORRECT — always import from domain modules
import { Room, CreditBundle, MembershipPlan } from '@/lib/domains/pricing';
import { Client } from '@/lib/domains/clients';
import { Booking, Invoice } from '@/lib/domains/bookings';
import { AppSetting, MarketingMedia } from '@/lib/domains/system';
import { User, Invite } from '@/lib/domains/users';
```

```js
// WRONG — deprecated facade, do not use
import { data as api } from '@/lib/data';
api.entities.Room.list()     // ❌
api.entities.Client.filter() // ❌
```

### Entity → Domain Module

| Entity | Import from |
|---|---|
| Room, AddOn, GlobalAddOn, Service, MembershipPlan, CreditBundle, CreditPackage, CreditConfiguration, CreditPricingTier, PricingSettings, PricingItem, RoomPricing | `@/lib/domains/pricing` |
| Client, ClientComplianceRecord, ClientSubscription, CreditTransaction, StripeCustomer, ClientPIN | `@/lib/domains/clients` |
| User, UserProfile, AdminRole, Invite | `@/lib/domains/users` |
| Booking, BookingAccessWindow, BookingExtensionRequest, BookingGuestList, BookingNotification, Invoice, OperatingHours | `@/lib/domains/bookings` |
| AppSetting, SharedCalendarToken, Notification, MarketingMedia, HeroSettings, Expense, EmailCampaign, ImageCropHistory | `@/lib/domains/system` |
| LockIntegration, RoomLockMapping, OperatingHours, iPadSession, iPadCommand, SyncReviewItem, SyncState | `@/lib/domains/access-control` |

### Edge Functions — Still OK to Invoke Directly

These 6 have no domain wrapper yet. `api.functions.invoke()` is acceptable **only** for these:

| Function | Used for |
|---|---|
| `getRoomAvailability` | Availability slots |
| `googleCalendarManager` | Google Calendar sync |
| `processUnifiedPurchase` | Checkout / payment |
| `submitTourRequest` | Studio tour form |
| `createMembershipAccount` | Membership signup |
| `submitContactForm` | Contact form |

---

## 7. Architecture Rules

1. **No inline domain logic in pages or components.** All data ops through `@/lib/domains/*`.
2. **No inline price math.** Only `pricingEngine.ts`.
3. **No direct `supabase.*` calls** outside `supabaseClient.ts`, `src/lib/domains/*`, and `supabase.auth.*`.
4. **No bypassing `createBookingWorkflow()`.** All booking creation goes through it.
5. **Admin pages use `AdminPageWrapper` + `PortalTopBar`.** No standalone page layouts.
6. **Supabase RLS is live.** Do not relax policies.
7. **Booking system internals are owned by a separate Claude chat.** Do not modify booking core logic unless explicitly coordinated.

---

## 8. Token Parity Table (current state)

| Token / Alias | `48labs-design` | `48labs-portal` | `48labs-website` |
|---|---|---|---|
| CSS custom properties | Baseline only | Baseline + `--interactive-hover` + status colors | Baseline + `--interactive-hover` + `--panel-elevated #243347` |
| Tailwind: raw token names | ✅ | ✅ | ✅ |
| Tailwind: semantic aliases | ❌ (not present) | ✅ full layer + status | ✅ full layer (no status) |
| `data-theme` on `<html>` | varies per page | togglable (light/dark) | fixed `dark` |
