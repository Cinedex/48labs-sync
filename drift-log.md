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
