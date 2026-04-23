# drift-log

Human-readable record of what drifted between 48labs-design and 48labs-sync, and how it was resolved.

## Format

Each entry shows:
- Date and commit hash
- Classification of changes: NEW (base44 additions), MODIFIED (already-Claude files), CONFLICT (Claude owns these files and they shifted in design)
- Brief summary

---

[2026-04-20 04:07 UTC] 47b2dd66: feat: move design site to cloudflare pages
  NEW: 3, MODIFIED: 1, CONFLICT: 0
  New: project.config.json, public/_redirects, scripts/deploy-guard.mjs
[2026-04-22 05:04 UTC] 762ca5e0: sync: UI primitives — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 10
  Conflict: src/components/ui/EmptyState.jsx, src/components/ui/FilterPills.jsx, src/components/ui/PortalDrawer.jsx, src/components/ui/PortalTable.jsx, src/components/ui/SearchInput.jsx (+5 more)
[2026-04-22 05:04 UTC] 18e25d25: sync: booking components — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 2
  Conflict: src/components/booking/BookingDateTimeStep.jsx, src/components/booking/ClientSelectStep.jsx
[2026-04-22 05:04 UTC] 923b30e2: sync: marketing components — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 3
  Conflict: src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/marketing/RoomOperatingHoursDisplay.jsx
[2026-04-22 05:04 UTC] 3564003b: sync: RoomForm components — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 2
  Conflict: src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx
[2026-04-22 05:04 UTC] 38853339: sync: dashboard and iPad components — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 3
  Conflict: src/components/dashboard/MonthCalendar.jsx, src/components/ipad/FiveMinWarning.jsx, src/components/ipad/ThankYouScreen.jsx
[2026-04-22 05:04 UTC] 22cdea70: sync: BookingFlow.jsx — refined version from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 1
  Conflict: src/pages/BookingFlow.jsx
[2026-04-22 05:04 UTC] f19cdf03: sync: website marketing pages — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 4
  Conflict: src/pages/Landing.jsx, src/pages/RoomProfile.jsx, src/pages/Services.jsx, src/pages/Studios.jsx
[2026-04-22 05:04 UTC] aa4661f4: sync: website booking and auth pages — refined versions from Claude Code
  NEW: 0, MODIFIED: 0, CONFLICT: 6
  Conflict: src/pages/DynamicCreditsPage.jsx, src/pages/DynamicMembershipsPage.jsx, src/pages/GuestBuyCredits.jsx, src/pages/MembershipSignup.jsx, src/pages/Register.jsx (+1 more)
[2026-04-22 15:33 UTC] dcb2a8e9: merge: bring staging sync commits into main (Phase 3 design sync)
  NEW: 3, MODIFIED: 1, CONFLICT: 31
  Conflict: src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx, src/components/booking/BookingDateTimeStep.jsx (+26 more)
## dcb2a8e9 — merge: bring staging sync commits into main (Phase 3 design sync)

**Date:** 2026-04-22T15:33:13Z

**Classification:** 3× NEW, 32× MODIFIED, 31× CONFLICT  

**Files:**
- package.json (MODIFIED)
- project.config.json (NEW)
- public/_redirects (NEW)
- scripts/deploy-guard.mjs (NEW)
- src/components/MarketingFooter.jsx (CONFLICT)
- src/components/MarketingHeader.jsx (CONFLICT)
- src/components/RoomForm/RoomStudioPreview.jsx (CONFLICT)
- src/components/RoomForm/WebsitePreviewCard.jsx (CONFLICT)
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/components/booking/ClientSelectStep.jsx (CONFLICT)
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/ipad/FiveMinWarning.jsx (CONFLICT)
- src/components/ipad/ThankYouScreen.jsx (CONFLICT)
- src/components/marketing/RoomOperatingHoursDisplay.jsx (CONFLICT)
- src/components/ui/EmptyState.jsx (CONFLICT)
- src/components/ui/FilterPills.jsx (CONFLICT)
- src/components/ui/PortalDrawer.jsx (CONFLICT)
- src/components/ui/PortalTable.jsx (CONFLICT)
- src/components/ui/SearchInput.jsx (CONFLICT)
- src/components/ui/SegmentedControl.jsx (CONFLICT)
- ... and 15 more files

---

## aa4661f4 — sync: website booking and auth pages — refined versions from Claude Code

**Date:** 2026-04-22T05:04:47Z

**Classification:** 0× NEW, 6× MODIFIED, 6× CONFLICT  

**Files:**
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/pages/GuestBuyCredits.jsx (CONFLICT)
- src/pages/MembershipSignup.jsx (CONFLICT)
- src/pages/Register.jsx (CONFLICT)
- src/pages/UnifiedCheckout.jsx (CONFLICT)

---

## f19cdf03 — sync: website marketing pages — refined versions from Claude Code

**Date:** 2026-04-22T05:04:42Z

**Classification:** 0× NEW, 4× MODIFIED, 4× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/pages/Services.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)

---

## 22cdea70 — sync: BookingFlow.jsx — refined version from Claude Code

**Date:** 2026-04-22T05:04:36Z

**Classification:** 0× NEW, 1× MODIFIED, 1× CONFLICT  

**Files:**
- src/pages/BookingFlow.jsx (CONFLICT)

---

## 38853339 — sync: dashboard and iPad components — refined versions from Claude Code

**Date:** 2026-04-22T05:04:31Z

**Classification:** 0× NEW, 3× MODIFIED, 3× CONFLICT  

**Files:**
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/ipad/FiveMinWarning.jsx (CONFLICT)
- src/components/ipad/ThankYouScreen.jsx (CONFLICT)

---

## 3564003b — sync: RoomForm components — refined versions from Claude Code

**Date:** 2026-04-22T05:04:23Z

**Classification:** 0× NEW, 2× MODIFIED, 2× CONFLICT  

**Files:**
- src/components/RoomForm/RoomStudioPreview.jsx (CONFLICT)
- src/components/RoomForm/WebsitePreviewCard.jsx (CONFLICT)

---

## 923b30e2 — sync: marketing components — refined versions from Claude Code

**Date:** 2026-04-22T05:04:19Z

**Classification:** 0× NEW, 3× MODIFIED, 3× CONFLICT  

**Files:**
- src/components/MarketingFooter.jsx (CONFLICT)
- src/components/MarketingHeader.jsx (CONFLICT)
- src/components/marketing/RoomOperatingHoursDisplay.jsx (CONFLICT)

---

## 18e25d25 — sync: booking components — refined versions from Claude Code

**Date:** 2026-04-22T05:04:15Z

**Classification:** 0× NEW, 2× MODIFIED, 2× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/components/booking/ClientSelectStep.jsx (CONFLICT)

---

## 762ca5e0 — sync: UI primitives — refined versions from Claude Code

**Date:** 2026-04-22T05:04:10Z

**Classification:** 0× NEW, 10× MODIFIED, 10× CONFLICT  

**Files:**
- src/components/ui/EmptyState.jsx (CONFLICT)
- src/components/ui/FilterPills.jsx (CONFLICT)
- src/components/ui/PortalDrawer.jsx (CONFLICT)
- src/components/ui/PortalTable.jsx (CONFLICT)
- src/components/ui/SearchInput.jsx (CONFLICT)
- src/components/ui/SegmentedControl.jsx (CONFLICT)
- src/components/ui/SettingCard.jsx (CONFLICT)
- src/components/ui/Spinner.jsx (CONFLICT)
- src/components/ui/TabBar.jsx (CONFLICT)
- src/components/ui/button.jsx (CONFLICT)

---

## 47b2dd66 — feat: move design site to cloudflare pages

**Date:** 2026-04-20T04:07:52Z

**Classification:** 3× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- package.json (MODIFIED)
- project.config.json (NEW)
- public/_redirects (NEW)
- scripts/deploy-guard.mjs (NEW)

---

## 725cf756 — Update base44 packages

**Date:** 2026-04-12T15:14:18Z

**Classification:** 0× NEW, 2× MODIFIED, 0× CONFLICT  

**Files:**
- package-lock.json (MODIFIED)
- package.json (MODIFIED)

---

## fe64f268 — File changes

**Date:** 2026-04-12T01:46:59Z

**Classification:** 2× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/database/MIGRATION_REPORT.md (MODIFIED)
- src/database/data-migration-plan.md (NEW)
- src/database/migration-order.json (NEW)
- src/database/supabase/schema.sql (MODIFIED)
- src/database/types/schema.ts (MODIFIED)

---

## 62d1e6a5 — File changes

**Date:** 2026-04-12T01:42:54Z

**Classification:** 0× NEW, 2× MODIFIED, 0× CONFLICT  

**Files:**
- src/lib/workflow-data.js (MODIFIED)
- src/pages/AdminWorkflowMap.jsx (MODIFIED)

---

## eb00c62f — File changes

**Date:** 2026-04-12T01:40:38Z

**Classification:** 0× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

## fe80272b — File changes

**Date:** 2026-04-12T01:37:07Z

**Classification:** 7× NEW, 0× MODIFIED, 0× CONFLICT  

**Files:**
- src/contracts/schema/enums.json (NEW)
- src/contracts/schema/relationships.json (NEW)
- src/contracts/schema/tables.json (NEW)
- src/database/MIGRATION_REPORT.md (NEW)
- src/database/mappings/base44-map.ts (NEW)
- src/database/supabase/schema.sql (NEW)
- src/database/types/schema.ts (NEW)

---

## cc98d284 — File changes

**Date:** 2026-04-12T01:29:03Z

**Classification:** 0× NEW, 6× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/RoomLightingLayout.jsonc (MODIFIED)
- base44/entities/iPadCommand.jsonc (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/LightingPanel.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)

---

## e2e0de2e — File changes

**Date:** 2026-04-12T01:22:17Z

**Classification:** 0× NEW, 1× MODIFIED, 1× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)

---

## 96400df4 — File changes

**Date:** 2026-04-12T00:52:59Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

## e4b13f4b — File changes

**Date:** 2026-04-12T00:49:05Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/lib/workflow-data.js (MODIFIED)

---

## 0a8d94c4 — File changes

**Date:** 2026-04-12T00:43:22Z

**Classification:** 0× NEW, 2× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)

---

## 0ddc5140 — File changes

**Date:** 2026-04-12T00:39:19Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

## 01ef5f43 — File changes

**Date:** 2026-04-12T00:30:30Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/pages/AdminWorkflowMap.jsx (MODIFIED)

---

## cc795b75 — File changes

**Date:** 2026-04-12T00:23:25Z

**Classification:** 0× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## e9c7dad7 — File changes

**Date:** 2026-04-12T00:20:40Z

**Classification:** 0× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

## dc5b801f — File changes

**Date:** 2026-04-12T00:03:02Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## 1aec1f99 — File changes

**Date:** 2026-04-11T23:54:19Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- tailwind.config.js (MODIFIED)

---

## 3f83184f — File changes

**Date:** 2026-04-11T23:52:52Z

**Classification:** 0× NEW, 7× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/components/dashboard/FloatingDayPanel.jsx (MODIFIED)
- src/components/dashboard/SessionTimelineCard.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)
- src/index.css (MODIFIED)
- tailwind.config.js (MODIFIED)

---

## 0e0a4d29 — File changes

**Date:** 2026-04-11T23:22:13Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/pages/StudioController.jsx (MODIFIED)

---

## 7e2cf42d — File changes

**Date:** 2026-04-11T21:26:07Z

**Classification:** 2× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)
- src/components/ipad/DemoScreen.jsx (NEW)
- src/components/ipad/IdleScreen.jsx (NEW)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## ca56f4c8 — File changes

**Date:** 2026-04-11T21:23:51Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)

---

## 7bd3f848 — File changes

**Date:** 2026-04-11T17:53:09Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/LightingPanel.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## 5756d26d — File changes

**Date:** 2026-04-11T17:33:38Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)

---

## b3b4a959 — File changes

**Date:** 2026-04-11T17:21:37Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/index.css (MODIFIED)

---

## 442a4aa6 — File changes

**Date:** 2026-04-11T17:07:18Z

**Classification:** 0× NEW, 4× MODIFIED, 1× CONFLICT  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/hooks/useTheme.js (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

## d4df16bd — File changes

**Date:** 2026-04-11T16:54:44Z

**Classification:** 1× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/dashboard/FloatingEventPanel.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

## d37f5413 — File changes

**Date:** 2026-04-11T16:49:42Z

**Classification:** 0× NEW, 5× MODIFIED, 1× CONFLICT  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/hooks/useTheme.js (MODIFIED)

---

## 981bd655 — File changes

**Date:** 2026-04-11T16:46:39Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/pages/CustomLogin.jsx (MODIFIED)

---

## 3a1682a1 — File changes

**Date:** 2026-04-11T16:45:25Z

**Classification:** 2× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/iPadCommand.jsonc (NEW)
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/iPadVersionControl/entry.ts (NEW)
- index.html (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## 18612a7d — File changes

**Date:** 2026-04-11T16:40:47Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

## ad879b0b — File changes

**Date:** 2026-04-11T16:39:39Z

**Classification:** 3× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/RoomLightingLayout.jsonc (NEW)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ipad/CircularThermostat.jsx (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/MasterIPadView.jsx (NEW)
- src/pages/StudioController.jsx (MODIFIED)

---

## ae210dd2 — File changes

**Date:** 2026-04-11T16:36:30Z

**Classification:** 1× NEW, 4× MODIFIED, 1× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

## 1c572b9d — File changes

**Date:** 2026-04-11T06:41:13Z

**Classification:** 2× NEW, 6× MODIFIED, 0× CONFLICT  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)
- src/components/ipad/BackgroundLayer.jsx (NEW)
- src/components/ipad/CircularThermostat.jsx (NEW)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

## c2e86504 — File changes

**Date:** 2026-04-11T06:36:48Z

**Classification:** 0× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

## 9098ede4 — File changes

**Date:** 2026-04-11T06:28:01Z

**Classification:** 0× NEW, 2× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)

---

## c323e33f — File changes

**Date:** 2026-04-11T06:23:32Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)

---

## a32f6aaf — File changes

**Date:** 2026-04-11T06:22:32Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)

---

## 405ff264 — File changes

**Date:** 2026-04-11T06:14:43Z

**Classification:** 0× NEW, 4× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)

---

## d6bc2b03 — File changes

**Date:** 2026-04-11T06:05:34Z

**Classification:** 0× NEW, 1× MODIFIED, 0× CONFLICT  

**Files:**
- src/pages/CustomLogin.jsx (MODIFIED)

---

## e90d8ade — File changes

**Date:** 2026-04-11T06:00:19Z

**Classification:** 0× NEW, 3× MODIFIED, 0× CONFLICT  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---


### dcb2a8e — 2026-04-22T15:33:13Z
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files:** 35 changed
**Summary:** 3× NEW, 32× MODIFIED, 0× CONFLICT

### aa4661f — 2026-04-22T05:04:47Z
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files:** 6 changed
**Summary:** 0× NEW, 6× MODIFIED, 0× CONFLICT

### f19cdf0 — 2026-04-22T05:04:42Z
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files:** 4 changed
**Summary:** 0× NEW, 4× MODIFIED, 0× CONFLICT

### 22cdea7 — 2026-04-22T05:04:36Z
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files:** 1 changed
**Summary:** 0× NEW, 1× MODIFIED, 0× CONFLICT

### 3885333 — 2026-04-22T05:04:31Z
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files:** 3 changed
**Summary:** 0× NEW, 3× MODIFIED, 0× CONFLICT

### 3564003 — 2026-04-22T05:04:23Z
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files:** 2 changed
**Summary:** 0× NEW, 2× MODIFIED, 0× CONFLICT

### 923b30e — 2026-04-22T05:04:19Z
**Message:** sync: marketing components — refined versions from Claude Code
**Files:** 3 changed
**Summary:** 0× NEW, 3× MODIFIED, 0× CONFLICT

### 18e25d2 — 2026-04-22T05:04:15Z
**Message:** sync: booking components — refined versions from Claude Code
**Files:** 2 changed
**Summary:** 0× NEW, 2× MODIFIED, 0× CONFLICT

### 762ca5e — 2026-04-22T05:04:10Z
**Message:** sync: UI primitives — refined versions from Claude Code
**Files:** 10 changed
**Summary:** 0× NEW, 10× MODIFIED, 0× CONFLICT

### 47b2dd6 — 2026-04-20T04:07:52Z
**Message:** feat: move design site to cloudflare pages
**Files:** 4 changed
**Summary:** 3× NEW, 1× MODIFIED, 0× CONFLICT
