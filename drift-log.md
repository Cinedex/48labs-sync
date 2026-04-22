# Drift Log

Tracks token, config, and structural drift between `48labs-design`, `48labs-website`, and `48labs-portal`.
Each entry records what diverged, which repo leads, and the resolution action taken.

---

## 2026-04-21 — Phase 1 Step 1: CSS variables and Tailwind alias parity

### Drift resolved

**`--interactive-hover` CSS variable**
- **Drift**: Portal defined it; design and website did not.
- **Resolution**: Added to `48labs-website/src/index.css` (light: `rgba(0,0,0,0.06)`, dark: `rgba(255,255,255,0.08)`). Design left as-is (read-only reference).

**`--panel-elevated` dark mode value**
- **Drift**: All three repos had `#1E293B` — same as `--panel-bg`. No visual distinction between surface and elevated in dark mode.
- **Resolution**: Updated `48labs-website/src/index.css` dark `--panel-elevated` to `#243347`. Portal left at `#1E293B` (intentionally not changed — portal decision to make separately).

**Tailwind semantic alias layer**
- **Drift**: Portal had full semantic alias layer (`canvas`, `surface`, `elevated`, `on-surface`, `on-surface-secondary`, `on-surface-muted`, `border-soft`, `border-hard`, `interactive`). Website and design had only raw token names.
- **Resolution**: Added full alias layer to `48labs-website/tailwind.config.js` verbatim from portal. Status color aliases omitted (website doesn't use booking-status pills). Design left as-is.

### Remaining known drift

| Item | Portal | Website | Action |
|---|---|---|---|
| `--panel-elevated` dark | `#1E293B` (= panel-bg) | `#243347` | Portal to be updated separately |
| Status color aliases | ✅ in tailwind | — | Not needed for website |
| `--interactive-hover` in design | — | ✅ | Design is read-only, no action |

---

## 2026-04-21 — Phase 1 Step 2: Shared component primitives

### Drift resolved

**`data-theme` not set on website `<html>`**
- **Drift**: `48labs-website/index.html` had no `data-theme` attribute — CSS custom property tokens (`--text-muted`, `--border-subtle`, etc.) resolved to undefined across the entire website.
- **Resolution**: Added `data-theme="dark"` to `<html>`. Website is permanently dark (marketing site). No theme toggle needed.

**`button.jsx` outline variant**
- **Drift**: Website used `border-slate-600 text-slate-200 hover:bg-slate-700 hover:text-white`. Portal used semantic tokens.
- **Resolution**: Updated website `button.jsx` to match portal: `border-border-hard text-on-surface hover:bg-elevated hover:text-on-surface`.

**`MarketingHeader.jsx` and `MarketingFooter.jsx`**
- **Drift**: `api.entities.AppSetting.filter()` (old data facade). `slate-*` hardcoded tokens throughout.
- **Resolution**: Replaced with `getAppSettingByKey()` from `@/lib/domains/system`. All `slate-300/400/500/700/800` → `text-on-surface-secondary/muted`, `border-border-soft`, `hover:bg-interactive`.

### Remaining known drift (website)

Booking/GuestBooking/Checkout/marketing/services components still have hardcoded slate/white values. These render on intentionally dark pages — addressed in Step 3 (website pages).

---

## 2026-04-21 — Phase 1 Step 3: Website pages token compliance

### Drift resolved

**Hardcoded `slate-*` tokens across 36 website pages and components**
- **Drift**: `bg-slate-950/900/800/700/600`, `text-slate-200–700`, `border-slate-500–900` throughout all website pages and components.
- **Resolution**: Batch-replaced via Python regex. `bg-slate-*` → `bg-canvas/elevated`, `text-slate-*` → `text-on-surface/secondary/muted`, `border-slate-*` → `border-border-soft/hard`, `hover:bg-slate-*` → `hover:bg-interactive`.

**Gradient slate tokens (6 files)**
- `from-slate-900/via-slate-800/to-slate-800` → `from-canvas/via-elevated/to-elevated`

**`placeholder-slate-*` Tailwind v2 format (6 files)**
- Replaced with `placeholder:text-on-surface-muted` (v3 format)

**Solid `text-white` in non-button contexts (45 files)**
- Replaced with `text-on-surface`. `text-white/xx` opacity variants (used in Landing.jsx and GuestBooking.jsx for luminance layering on `bg-[#0a0a0a]` pages) intentionally preserved — no semantic token equivalent.

### Remaining known drift

| Item | Status |
|---|---|
| `text-white` on CTA buttons | Correct — intentional on colored backgrounds |
| `text-white/xx` opacity variants | Correct — intentional design effect, no token equivalent |
| Step 4: Booking engine (website-facing) | PENDING |
| Step 5: Portal pages | PENDING |
| Step 6: Booking engine (portal-facing) | PENDING |

---

## 2026-04-21 — Phase 1 Step 4: Booking engine (website-facing)

### Drift resolved

**`api.entities.*` data facade across 13 website files**
- **Drift**: Pages and components importing `{ data as api }` from `@/lib/data` and calling `api.entities.Room`, `api.entities.CreditBundle`, etc.
- **Resolution**: Migrated all entity calls to direct domain imports. `data as api` import removed where no longer needed.
- **Entity → domain mapping**: `Room/AddOn/GlobalAddOn/Service/MembershipPlan/CreditBundle/CreditConfiguration/CreditPricingTier/PricingSettings/PricingItem` → `@/lib/domains/pricing`; `MarketingMedia/HeroSettings` → `@/lib/domains/system`; `Client` → `@/lib/domains/clients`; `Invite` → `@/lib/domains/users`; `OperatingHours` → `@/lib/domains/bookings`

### Remaining known drift

| Item | Files | Status |
|---|---|---|
| `api.functions.invoke()` calls | 8 files | Intentionally left — no domain equivalent yet for edge functions |
| Edge functions to domain-ify | processUnifiedPurchase, googleCalendarManager, getRoomAvailability, submitTourRequest, submitContactForm, createMembershipAccount | Future work |

---

## 2026-04-21 — Phase 1 Steps 5 & 6: Portal token compliance + booking engine audit

### Step 5: Portal pages token compliance

**Remaining slate-* gradient tokens (9 files)**
- **Drift**: `from-slate-950/900`, `via-slate-800/900`, `to-slate-800/950`, `bg-slate-950/900/800/700` in Landing, RoomProfile, Services, Studios, RoomStudioPreview, WebsitePreviewCard, ThankYouScreen (ipad), FiveMinWarning (ipad).
- **Resolution**: Replaced with `from-canvas/via-elevated/to-elevated` semantic tokens.

**`border-t-slate-700` tooltip arrows (MonthCalendar.jsx)**
- **Resolution**: `border-t-border-soft`

**`bg-white` headers in BookingFlow.jsx**
- **Drift**: Two `<header>` elements with `bg-white` on a theme-aware portal page.
- **Resolution**: `bg-canvas`

**Intentionally preserved**
- `bg-white/[0.0x]` and `border-white/[0.0x]` opacity overlays on forced-dark pages
- `text-white/xx` opacity variants (Landing, GuestBooking, About, OnboardingForm)
- Toggle thumbs, document preview backgrounds, signature image containers (`bg-white` in non-surface contexts)

### Step 6: Booking engine (portal-facing)

**Status**: Already complete from CLAIM-003 (Domain + Query Normalization). Zero `api.entities.*` found in portal pages/components at audit. No action required.

### Remaining known drift (portal)

| Item | Status |
|---|---|
| `api.functions.invoke()` calls | Stay until edge functions are wrapped in domain layer (future work) |
| `bg-white/[0.0x]` opacity variants | Intentional — forced-dark design effects |
| Vite chunking warnings | Pre-existing, not introduced by this work |

---

## Template

```
## YYYY-MM-DD — [Phase N Step N]: [title]

### Drift resolved

**[token or config name]**
- **Drift**: ...
- **Resolution**: ...

### Remaining known drift

| Item | Portal | Website | Action |
|---|---|---|---|
```

---

## 2026-04-22 03:09 UTC | `5b06f159`

**Commit:** `5b06f15999046b2df212649b4e5f540e9bc0d1c2`  
**Message:** Update base44 packages  
**Manifest:** (manifest.json found)  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `package-lock.json` | modified | **MODIFIED** | file not in manifest (+8/-8) |
| `package.json` | modified | **MODIFIED** | file not in manifest (+2/-2) |
| `src/components/ProtectedRoute.jsx` | added | **NEW** | file not in manifest and was added (+37/-0) |

**Summary:** 2× MODIFIED, 1× NEW
---

## 2026-04-12 00:49 UTC | `e4b13f4b`

**Commit:** `e4b13f4b4ffa56a6aa10c1852acc02ba5fe125c3`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/lib/workflow-data.js` | — | **MODIFIED** | Component library update |

**Summary:** 1× MODIFIED

---

## 2026-04-12 00:52 UTC | `96400df4`

**Commit:** `96400df49aa564844fdc690640b9581b15bdd6ff`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/components/Sidebar.jsx` | — | **MODIFIED** | Layout component refinement |
| `src/components/admin/AdminTopbar.jsx` | — | **MODIFIED** | Admin UI update |
| `src/components/dashboard/PremiumCalendar.jsx` | — | **MODIFIED** | Calendar component enhancement |

**Summary:** 3× MODIFIED

---

## 2026-04-12 01:22 UTC | `e2e0de2e`

**Commit:** `e2e0de2e9943d041f64e0079bcb70868de708445`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/pages/Landing.jsx` | — | **MODIFIED** | Marketing page content update |

**Summary:** 1× MODIFIED

---

## 2026-04-12 01:29 UTC | `cc98d284`

**Commit:** `cc98d2849c95fef0146959877abacb2938c2ef5d`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `base44/entities/RoomLightingLayout.jsonc` | — | **NEW** | New Base44 entity schema |
| `base44/entities/iPadCommand.jsonc` | — | **NEW** | New Base44 entity schema |
| `src/components/ipad/InSessionScreen.jsx` | — | **MODIFIED** | iPad UI component update |
| `src/components/ipad/LightingCanvas.jsx` | — | **MODIFIED** | Lighting control component |
| `src/components/ipad/LightingPanel.jsx` | — | **MODIFIED** | Lighting panel enhancement |
| `src/components/ipad/MasterIPadView.jsx` | — | **MODIFIED** | iPad main view refactor |

**Summary:** 2× NEW, 4× MODIFIED

**Notes:** Base44 added new entity schemas for room lighting and iPad commands. Associated component implementations updated to integrate with new schema.

---

## 2026-04-12 01:37 UTC | `fe80272b`

**Commit:** `fe80272bfb6055d2e1026886589661cc83769a3f`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/contracts/schema/enums.json` | — | **NEW** | New Base44 schema contract |
| `src/contracts/schema/relationships.json` | — | **NEW** | New Base44 schema contract |
| `src/contracts/schema/tables.json` | — | **NEW** | New Base44 schema contract |
| `src/database/MIGRATION_REPORT.md` | — | **NEW** | Database migration documentation |
| `src/database/mappings/base44-map.ts` | — | **NEW** | Base44 entity mapping layer |
| `src/database/supabase/schema.sql` | — | **NEW** | Supabase schema definition |
| `src/database/types/schema.ts` | — | **NEW** | TypeScript schema type definitions |

**Summary:** 7× NEW

**Notes:** Major database foundation layer added. Includes schema contracts, migration docs, Base44 entity mappings, and Supabase schema. TypeScript types for full type safety.

---

## 2026-04-12 01:46 UTC | `fe64f268`

**Commit:** `fe64f268e2f246d72f201c0adac867d790e898e8`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/database/MIGRATION_REPORT.md` | — | **NEW** | Migration planning document |
| `src/database/data-migration-plan.md` | — | **NEW** | Data migration strategy |
| `src/database/migration-order.json` | — | **NEW** | Migration sequence definition |
| `src/database/supabase/schema.sql` | — | **NEW** | Supabase schema update |
| `src/database/types/schema.ts` | — | **NEW** | TypeScript type update |

**Summary:** 5× NEW

**Notes:** Database migration planning layer. Includes data migration strategy, sequence order, and schema/type updates.

---

## 2026-04-12 01:40 UTC | `eb00c62f`

**Commit:** `eb00c62f1af37502b179c033273c902adccd4c7a`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/components/Sidebar.jsx` | — | **MODIFIED** | Layout refinement |
| `src/components/admin/AdminTopbar.jsx` | — | **MODIFIED** | Admin header update |
| `src/components/admin/QuickActionsDropdown.jsx` | — | **MODIFIED** | Admin action menu |
| `src/components/dashboard/PremiumCalendar.jsx` | — | **MODIFIED** | Premium calendar feature |

**Summary:** 4× MODIFIED

---

## 2026-04-12 01:42 UTC | `62d1e6a5`

**Commit:** `62d1e6a5edcaf41329af9b5f5a8662f0fb92c7a1`  
**Message:** File changes  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `src/lib/workflow-data.js` | — | **MODIFIED** | Workflow data model update |
| `src/pages/AdminWorkflowMap.jsx` | — | **MODIFIED** | Admin workflow visualization |

**Summary:** 2× MODIFIED

---

## 2026-04-12 15:14 UTC | `725cf756`

**Commit:** `725cf75610745a0dcb530f28afef0174826e5d44`  
**Message:** Update base44 packages  

| File | Git Status | Classification | Notes |
|------|-----------|---------------|-------|
| `package.json` | — | **MODIFIED** | Dependency update |
| `package-lock.json` | — | **MODIFIED** | Lockfile update |

**Summary:** 2× MODIFIED

**Notes:** Base44 SDK and related packages updated.

## 2026-04-12 — Phase 2 Setup: Commit monitoring

### Changes logged

**e4b13f4** — 1× MODIFIED
- `src/lib/workflow-data.js`: Updated workflow data structure

**96400df** — 3× MODIFIED
- `src/components/Sidebar.jsx`, `src/components/admin/AdminTopbar.jsx`, `src/components/dashboard/PremiumCalendar.jsx`: Component refinements

**e2e0de2** — 1× **CONFLICT** ⚠️
- `src/pages/Landing.jsx`: Modified — this file is owned by Claude Code (`CLAUDE_STANDARDS.md`, Phase 1 Step 3). Requires review before merge.

**cc98d28** — 6× MODIFIED
- `base44/entities/RoomLightingLayout.jsonc`, `base44/entities/iPadCommand.jsonc`: New entities added
- `src/components/ipad/InSessionScreen.jsx`, `src/components/ipad/LightingCanvas.jsx`, `src/components/ipad/LightingPanel.jsx`, `src/components/ipad/MasterIPadView.jsx`: iPad integration components

**fe80272** — 7× NEW
- `src/contracts/schema/`: Contract system foundation (enums, relationships, tables)
- `src/database/`: Migration support, Supabase schema, type mappings (`schema.ts`, `base44-map.ts`, `supabase/schema.sql`)
- `src/database/MIGRATION_REPORT.md`: Migration documentation

**fe64f26** — 2× NEW, 3× MODIFIED
- `src/database/data-migration-plan.md`, `src/database/migration-order.json`: NEW — migration planning documents
- `src/database/MIGRATION_REPORT.md`, `src/database/supabase/schema.sql`, `src/database/types/schema.ts`: MODIFIED — schema and report updates

**62d1e6a** — 2× MODIFIED
- `src/lib/workflow-data.js`, `src/pages/AdminWorkflowMap.jsx`: Workflow enhancements

**eb00c62** — 4× MODIFIED
- `src/components/Sidebar.jsx`, `src/components/admin/AdminTopbar.jsx`, `src/components/admin/QuickActionsDropdown.jsx`, `src/components/dashboard/PremiumCalendar.jsx`: Admin UI refinements

**725cf75** — 2× MODIFIED
- `package.json`, `package-lock.json`: Base44 package updates

### No new conflicts detected

All changes are NEW (database/contract system foundation) or MODIFIED (component/workflow refinements). One CONFLICT flag: `Landing.jsx` owned by Claude Code — verify changes align with Phase 1 token/domain standards before pulling into portal or website.

---
