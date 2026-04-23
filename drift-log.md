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
### 2026-04-22 — dcb2a8e9
**Commit:** `dcb2a8e911e5ed365732b984c6e920f1ced3d844`  
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)  
**Classification:** 31× CONFLICT, 4× MODIFIED  

**Files:**
- package.json (MODIFIED)
- project.config.json (MODIFIED)
- public/_redirects (MODIFIED)
- scripts/deploy-guard.mjs (MODIFIED)
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
- src/components/ui/SettingCard.jsx (CONFLICT)
- src/components/ui/Spinner.jsx (CONFLICT)
- src/components/ui/TabBar.jsx (CONFLICT)
- src/components/ui/button.jsx (CONFLICT)
- src/pages/BookingFlow.jsx (CONFLICT)
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/pages/GuestBuyCredits.jsx (CONFLICT)
- src/pages/Landing.jsx (CONFLICT)
- src/pages/MembershipSignup.jsx (CONFLICT)
- src/pages/Register.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/pages/Services.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)
- src/pages/UnifiedCheckout.jsx (CONFLICT)

---

### 2026-04-22 — aa4661f4
**Commit:** `aa4661f4b14bfb0d815b78f4a1206cd07a2810f4`  
**Message:** sync: website booking and auth pages — refined versions from Claude Code  
**Classification:** 6× CONFLICT  

**Files:**
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/pages/GuestBuyCredits.jsx (CONFLICT)
- src/pages/MembershipSignup.jsx (CONFLICT)
- src/pages/Register.jsx (CONFLICT)
- src/pages/UnifiedCheckout.jsx (CONFLICT)

---

### 2026-04-22 — f19cdf03
**Commit:** `f19cdf0381be3ceebc40ae98c2bc71f92148d855`  
**Message:** sync: website marketing pages — refined versions from Claude Code  
**Classification:** 4× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/pages/Services.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)

---

### 2026-04-22 — 22cdea70
**Commit:** `22cdea70afd9f763b36b3e1941e366c04b97b1e6`  
**Message:** sync: BookingFlow.jsx — refined version from Claude Code  
**Classification:** 1× CONFLICT  

**Files:**
- src/pages/BookingFlow.jsx (CONFLICT)

---

### 2026-04-22 — 38853339
**Commit:** `38853339f47e5b2ddcd23a205c40cb228fcd8dc1`  
**Message:** sync: dashboard and iPad components — refined versions from Claude Code  
**Classification:** 3× CONFLICT  

**Files:**
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/ipad/FiveMinWarning.jsx (CONFLICT)
- src/components/ipad/ThankYouScreen.jsx (CONFLICT)

---

### 2026-04-22 — 3564003b
**Commit:** `3564003baf53a0ced6da5c5c49941f4d09c8082d`  
**Message:** sync: RoomForm components — refined versions from Claude Code  
**Classification:** 2× CONFLICT  

**Files:**
- src/components/RoomForm/RoomStudioPreview.jsx (CONFLICT)
- src/components/RoomForm/WebsitePreviewCard.jsx (CONFLICT)

---

### 2026-04-22 — 923b30e2
**Commit:** `923b30e2efc07529a161d81258b6bbda8daba496`  
**Message:** sync: marketing components — refined versions from Claude Code  
**Classification:** 3× CONFLICT  

**Files:**
- src/components/MarketingFooter.jsx (CONFLICT)
- src/components/MarketingHeader.jsx (CONFLICT)
- src/components/marketing/RoomOperatingHoursDisplay.jsx (CONFLICT)

---

### 2026-04-22 — 18e25d25
**Commit:** `18e25d254af8ee8569479173206fb9ea19d0382c`  
**Message:** sync: booking components — refined versions from Claude Code  
**Classification:** 2× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/components/booking/ClientSelectStep.jsx (CONFLICT)

---

### 2026-04-22 — 762ca5e0
**Commit:** `762ca5e09a65dd464932fe352920a4faacbfa0bc`  
**Message:** sync: UI primitives — refined versions from Claude Code  
**Classification:** 10× CONFLICT  

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

### 2026-04-20 — 47b2dd66
**Commit:** `47b2dd66260b5c9585f2b3c5cde7da1a130183f5`  
**Message:** feat: move design site to cloudflare pages  
**Classification:** 4× MODIFIED  

**Files:**
- package.json (MODIFIED)
- project.config.json (MODIFIED)
- public/_redirects (MODIFIED)
- scripts/deploy-guard.mjs (MODIFIED)

---

### 2026-04-16 — 5b06f159
**Commit:** `5b06f15999046b2df212649b4e5f540e9bc0d1c2`  
**Message:** Update base44 packages  
**Classification:** 3× MODIFIED  

**Files:**
- package-lock.json (MODIFIED)
- package.json (MODIFIED)
- src/components/ProtectedRoute.jsx (MODIFIED)

---

### 2026-04-12 — 725cf756
**Commit:** `725cf75610745a0dcb530f28afef0174826e5d44`  
**Message:** Update base44 packages  
**Classification:** 2× MODIFIED  

**Files:**
- package-lock.json (MODIFIED)
- package.json (MODIFIED)

---

### 2026-04-12 — fe64f268
**Commit:** `fe64f268e2f246d72f201c0adac867d790e898e8`  
**Message:** File changes  
**Classification:** 5× MODIFIED  

**Files:**
- src/database/MIGRATION_REPORT.md (MODIFIED)
- src/database/data-migration-plan.md (MODIFIED)
- src/database/migration-order.json (MODIFIED)
- src/database/supabase/schema.sql (MODIFIED)
- src/database/types/schema.ts (MODIFIED)

---

### 2026-04-12 — 62d1e6a5
**Commit:** `62d1e6a5edcaf41329af9b5f5a8662f0fb92c7a1`  
**Message:** File changes  
**Classification:** 2× MODIFIED  

**Files:**
- src/lib/workflow-data.js (MODIFIED)
- src/pages/AdminWorkflowMap.jsx (MODIFIED)

---

### 2026-04-12 — eb00c62f
**Commit:** `eb00c62f1af37502b179c033273c902adccd4c7a`  
**Message:** File changes  
**Classification:** 4× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

### 2026-04-12 — fe80272b
**Commit:** `fe80272bfb6055d2e1026886589661cc83769a3f`  
**Message:** File changes  
**Classification:** 7× MODIFIED  

**Files:**
- src/contracts/schema/enums.json (MODIFIED)
- src/contracts/schema/relationships.json (MODIFIED)
- src/contracts/schema/tables.json (MODIFIED)
- src/database/MIGRATION_REPORT.md (MODIFIED)
- src/database/mappings/base44-map.ts (MODIFIED)
- src/database/supabase/schema.sql (MODIFIED)
- src/database/types/schema.ts (MODIFIED)

---

### 2026-04-12 — cc98d284
**Commit:** `cc98d2849c95fef0146959877abacb2938c2ef5d`  
**Message:** File changes  
**Classification:** 6× MODIFIED  

**Files:**
- base44/entities/RoomLightingLayout.jsonc (MODIFIED)
- base44/entities/iPadCommand.jsonc (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/LightingPanel.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)

---

### 2026-04-12 — e2e0de2e
**Commit:** `e2e0de2e9943d041f64e0079bcb70868de708445`  
**Message:** File changes  
**Classification:** 1× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)

---

### 2026-04-12 — 96400df4
**Commit:** `96400df49aa564844fdc690640b9581b15bdd6ff`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

### 2026-04-12 — e4b13f4b
**Commit:** `e4b13f4b4ffa56a6aa10c1852acc02ba5fe125c3`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/lib/workflow-data.js (MODIFIED)

---

### 2026-04-12 — 0a8d94c4
**Commit:** `0a8d94c46d2c2daa6e99dd163e9afe0e38dc7fad`  
**Message:** File changes  
**Classification:** 2× MODIFIED  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)

---

### 2026-04-12 — 0ddc5140
**Commit:** `0ddc514060a5e7529847ccfc6e7470fc54e090cd`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

### 2026-04-12 — 01ef5f43
**Commit:** `01ef5f4337520e76403439b54f416474113f54df`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/pages/AdminWorkflowMap.jsx (MODIFIED)

---

### 2026-04-12 — cc795b75
**Commit:** `cc795b75b80fce9ec723d7af1b51fe1d89bf0403`  
**Message:** File changes  
**Classification:** 4× MODIFIED  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-12 — e9c7dad7
**Commit:** `e9c7dad7b6382d255dcaa79c6864ada1af6cff31`  
**Message:** File changes  
**Classification:** 4× MODIFIED  

**Files:**
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

### 2026-04-12 — dc5b801f
**Commit:** `dc5b801f9bbc0f3ad91f970ce659b8a8a5aa569c`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — 1aec1f99
**Commit:** `1aec1f99b66b04ecd17059309161e45bf7e777a7`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- tailwind.config.js (MODIFIED)

---

### 2026-04-11 — 3f83184f
**Commit:** `3f83184f91b4ab6e852e2bcc4b9237b86a3a172c`  
**Message:** File changes  
**Classification:** 7× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/components/dashboard/FloatingDayPanel.jsx (MODIFIED)
- src/components/dashboard/SessionTimelineCard.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)
- src/index.css (MODIFIED)
- tailwind.config.js (MODIFIED)

---

### 2026-04-11 — 0e0a4d29
**Commit:** `0e0a4d2977b02b9e0e2b7703a6fa5d216172ef53`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — 7e2cf42d
**Commit:** `7e2cf42d2b848cc0701c27b5bf19bca5f023ace5`  
**Message:** File changes  
**Classification:** 6× MODIFIED  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)
- src/components/ipad/DemoScreen.jsx (MODIFIED)
- src/components/ipad/IdleScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — ca56f4c8
**Commit:** `ca56f4c8408cc98b7f351cf33a29d0ccb11fd51a`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/DashboardMetricCard.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)

---

### 2026-04-11 — 7bd3f848
**Commit:** `7bd3f84826df6d0d27d9e3453556763266f6145e`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/LightingPanel.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — 5756d26d
**Commit:** `5756d26deafaed42b9568bf9599c2041cf8bde44`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)

---

### 2026-04-11 — b3b4a959
**Commit:** `b3b4a959f93f24b22ff5570d22bfd34f7cf5a7bf`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/index.css (MODIFIED)

---

### 2026-04-11 — 442a4aa6
**Commit:** `442a4aa6fd20a437134e2c4efd820733ff556cb2`  
**Message:** File changes  
**Classification:** 1× CONFLICT, 3× MODIFIED  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/hooks/useTheme.js (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

### 2026-04-11 — d4df16bd
**Commit:** `d4df16bd215b222c929d234467a3dbefbe039f07`  
**Message:** File changes  
**Classification:** 2× MODIFIED  

**Files:**
- src/components/dashboard/FloatingEventPanel.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

### 2026-04-11 — d37f5413
**Commit:** `d37f5413563affbbed94992addb58b64125adcb0`  
**Message:** File changes  
**Classification:** 1× CONFLICT, 4× MODIFIED  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/hooks/useTheme.js (MODIFIED)

---

### 2026-04-11 — 981bd655
**Commit:** `981bd65522efbfc84fbdcf1941d47c18993becc6`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/pages/CustomLogin.jsx (MODIFIED)

---

### 2026-04-11 — 3a1682a1
**Commit:** `3a1682a1fefffdc5826186363751d43dfa46464d`  
**Message:** File changes  
**Classification:** 6× MODIFIED  

**Files:**
- base44/entities/iPadCommand.jsonc (MODIFIED)
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/iPadVersionControl/entry.ts (MODIFIED)
- index.html (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — 18612a7d
**Commit:** `18612a7d50b178d093fa8126aef26915702c760a`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)

---

### 2026-04-11 — ad879b0b
**Commit:** `ad879b0b49a934ac4115c07661c78b8fe3ba6cc3`  
**Message:** File changes  
**Classification:** 7× MODIFIED  

**Files:**
- base44/entities/RoomLightingLayout.jsonc (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ipad/CircularThermostat.jsx (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/LightingCanvas.jsx (MODIFIED)
- src/components/ipad/MasterIPadView.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — ae210dd2
**Commit:** `ae210dd267db37ea0eb18787277cd0b8726c153b`  
**Message:** File changes  
**Classification:** 1× CONFLICT, 4× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

### 2026-04-11 — 1c572b9d
**Commit:** `1c572b9df1e37f5a5fc5d80a96f6d81e9fdfd6dc`  
**Message:** File changes  
**Classification:** 8× MODIFIED  

**Files:**
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)
- src/components/ipad/BackgroundLayer.jsx (MODIFIED)
- src/components/ipad/CircularThermostat.jsx (MODIFIED)
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)
- src/pages/AdminiPadController.jsx (MODIFIED)
- src/pages/StudioController.jsx (MODIFIED)

---

### 2026-04-11 — c2e86504
**Commit:** `c2e8650418eebbc1a50d5c2ebb6839ce2adeed49`  
**Message:** File changes  
**Classification:** 4× MODIFIED  

**Files:**
- src/components/admin/AdminTopbar.jsx (MODIFIED)
- src/components/admin/QuickActionsDropdown.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

### 2026-04-11 — 9098ede4
**Commit:** `9098ede4984a7a07e7d8e0cfd8577d4a7008ee96`  
**Message:** File changes  
**Classification:** 2× MODIFIED  

**Files:**
- src/components/ipad/InSessionScreen.jsx (MODIFIED)
- src/components/ipad/WelcomeScreen.jsx (MODIFIED)

---

### 2026-04-11 — c323e33f
**Commit:** `c323e33f986baffd4591304bb829aa07780e3cf1`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)

---

### 2026-04-11 — a32f6aaf
**Commit:** `a32f6aaf5c651c5fb4e0a9cfd0da3d058e619456`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)

---

### 2026-04-11 — 405ff264
**Commit:** `405ff2645dfa9116f45a10604c94db9f9720ab3c`  
**Message:** File changes  
**Classification:** 4× MODIFIED  

**Files:**
- src/components/AdminLayout.jsx (MODIFIED)
- src/components/Sidebar.jsx (MODIFIED)
- src/components/dashboard/PremiumCalendar.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)

---

### 2026-04-11 — d6bc2b03
**Commit:** `d6bc2b0353bf18864fc557c5844b5929794e7a66`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- src/pages/CustomLogin.jsx (MODIFIED)

---

### 2026-04-11 — e90d8ade
**Commit:** `e90d8ade0095f11aab3906ad29ec3d354bda70ff`  
**Message:** File changes  
**Classification:** 3× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (MODIFIED)
- src/hooks/useTheme.js (MODIFIED)
- src/pages/AdminDashboard.jsx (MODIFIED)

---

### 2026-04-22 — dcb2a8e9
**Commit:** `dcb2a8e911e5ed365732b984c6e920f1ced3d844`  
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)  
**Classification:** 4× MODIFIED, 31× CONFLICT  

**Files:**
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
- src/components/ui/SettingCard.jsx (CONFLICT)
- src/components/ui/Spinner.jsx (CONFLICT)
- src/components/ui/TabBar.jsx (CONFLICT)
- src/components/ui/button.jsx (CONFLICT)
- src/pages/BookingFlow.jsx (CONFLICT)
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/pages/GuestBuyCredits.jsx (CONFLICT)
- src/pages/Landing.jsx (CONFLICT)
- src/pages/MembershipSignup.jsx (CONFLICT)
- src/pages/Register.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/pages/Services.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)
- src/pages/UnifiedCheckout.jsx (CONFLICT)
- package.json (MODIFIED)
- project.config.json (MODIFIED)
- public/_redirects (MODIFIED)
- scripts/deploy-guard.mjs (MODIFIED)

---

### 2026-04-22 — aa4661f4
**Commit:** `aa4661f4b14bfb0d815b78f4a1206cd07a2810f4`  
**Message:** sync: website booking and auth pages — refined versions from Claude Co  
**Classification:** 6× CONFLICT  

**Files:**
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/pages/GuestBuyCredits.jsx (CONFLICT)
- src/pages/MembershipSignup.jsx (CONFLICT)
- src/pages/Register.jsx (CONFLICT)
- src/pages/UnifiedCheckout.jsx (CONFLICT)

---

### 2026-04-22 — f19cdf03
**Commit:** `f19cdf0381be3ceebc40ae98c2bc71f92148d855`  
**Message:** sync: website marketing pages — refined versions from Claude Code  
**Classification:** 4× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/pages/Services.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)

---

### 2026-04-22 — 22cdea70
**Commit:** `22cdea70afd9f763b36b3e1941e366c04b97b1e6`  
**Message:** sync: BookingFlow.jsx — refined version from Claude Code  
**Classification:** 1× CONFLICT  

**Files:**
- src/pages/BookingFlow.jsx (CONFLICT)

---

### 2026-04-22 — 38853339
**Commit:** `38853339f47e5b2ddcd23a205c40cb228fcd8dc1`  
**Message:** sync: dashboard and iPad components — refined versions from Claude Cod  
**Classification:** 3× CONFLICT  

**Files:**
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/ipad/FiveMinWarning.jsx (CONFLICT)
- src/components/ipad/ThankYouScreen.jsx (CONFLICT)

---

### 2026-04-22 — 3564003b
**Commit:** `3564003baf53a0ced6da5c5c49941f4d09c8082d`  
**Message:** sync: RoomForm components — refined versions from Claude Code  
**Classification:** 2× CONFLICT  

**Files:**
- src/components/RoomForm/RoomStudioPreview.jsx (CONFLICT)
- src/components/RoomForm/WebsitePreviewCard.jsx (CONFLICT)

---

### 2026-04-22 — 923b30e2
**Commit:** `923b30e2efc07529a161d81258b6bbda8daba496`  
**Message:** sync: marketing components — refined versions from Claude Code  
**Classification:** 3× CONFLICT  

**Files:**
- src/components/MarketingFooter.jsx (CONFLICT)
- src/components/MarketingHeader.jsx (CONFLICT)
- src/components/marketing/RoomOperatingHoursDisplay.jsx (CONFLICT)

---

### 2026-04-22 — 18e25d25
**Commit:** `18e25d254af8ee8569479173206fb9ea19d0382c`  
**Message:** sync: booking components — refined versions from Claude Code  
**Classification:** 2× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/components/booking/ClientSelectStep.jsx (CONFLICT)

---

### 2026-04-22 — 762ca5e0
**Commit:** `762ca5e09a65dd464932fe352920a4faacbfa0bc`  
**Message:** sync: UI primitives — refined versions from Claude Code  
**Classification:** 10× CONFLICT  

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

### 2026-04-20 — 47b2dd66
**Commit:** `47b2dd66260b5c9585f2b3c5cde7da1a130183f5`  
**Message:** feat: move design site to cloudflare pages  
**Classification:** 4× MODIFIED  

**Files:**
- package.json (MODIFIED)
- project.config.json (MODIFIED)
- public/_redirects (MODIFIED)
- scripts/deploy-guard.mjs (MODIFIED)

---

### 2026-04-12 — 725cf756
**Commit:** `725cf75610745a0dcb530f28afef0174826e5d44`  
**Message:** Update base44 packages  
**Classification:** 2× MODIFIED  

**Files:**
- package-lock.json (MODIFIED)
- package.json (MODIFIED)

---

### 2026-04-12 — fe64f268
**Commit:** `fe64f268e2f246d72f201c0adac867d790e898e8`  
**Message:** File changes  
**Classification:** 5× NEW  

**Files:**
- src/database/MIGRATION_REPORT.md (NEW)
- src/database/data-migration-plan.md (NEW)
- src/database/migration-order.json (NEW)
- src/database/supabase/schema.sql (NEW)
- src/database/types/schema.ts (NEW)

---

### 2026-04-12 — 62d1e6a5
**Commit:** `62d1e6a5edcaf41329af9b5f5a8662f0fb92c7a1`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/lib/workflow-data.js (NEW)
- src/pages/AdminWorkflowMap.jsx (NEW)

---

### 2026-04-12 — eb00c62f
**Commit:** `eb00c62f1af37502b179c033273c902adccd4c7a`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/components/admin/AdminTopbar.jsx (NEW)
- src/components/admin/QuickActionsDropdown.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)

---

### 2026-04-12 — fe80272b
**Commit:** `fe80272bfb6055d2e1026886589661cc83769a3f`  
**Message:** File changes  
**Classification:** 7× NEW  

**Files:**
- src/contracts/schema/enums.json (NEW)
- src/contracts/schema/relationships.json (NEW)
- src/contracts/schema/tables.json (NEW)
- src/database/MIGRATION_REPORT.md (NEW)
- src/database/mappings/base44-map.ts (NEW)
- src/database/supabase/schema.sql (NEW)
- src/database/types/schema.ts (NEW)

---

### 2026-04-12 — cc98d284
**Commit:** `cc98d2849c95fef0146959877abacb2938c2ef5d`  
**Message:** File changes  
**Classification:** 4× NEW, 2× MODIFIED  

**Files:**
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/LightingPanel.jsx (NEW)
- src/components/ipad/MasterIPadView.jsx (NEW)
- base44/entities/RoomLightingLayout.jsonc (MODIFIED)
- base44/entities/iPadCommand.jsonc (MODIFIED)

---

### 2026-04-12 — e2e0de2e
**Commit:** `e2e0de2e9943d041f64e0079bcb70868de708445`  
**Message:** File changes  
**Classification:** 1× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)

---

### 2026-04-12 — 96400df4
**Commit:** `96400df49aa564844fdc690640b9581b15bdd6ff`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/components/admin/AdminTopbar.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)

---

### 2026-04-12 — e4b13f4b
**Commit:** `e4b13f4b4ffa56a6aa10c1852acc02ba5fe125c3`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/lib/workflow-data.js (NEW)

---

### 2026-04-12 — 0a8d94c4
**Commit:** `0a8d94c46d2c2daa6e99dd163e9afe0e38dc7fad`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/MasterIPadView.jsx (NEW)

---

### 2026-04-12 — 0ddc5140
**Commit:** `0ddc514060a5e7529847ccfc6e7470fc54e090cd`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/components/admin/AdminTopbar.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)

---

### 2026-04-12 — 01ef5f43
**Commit:** `01ef5f4337520e76403439b54f416474113f54df`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/AdminWorkflowMap.jsx (NEW)

---

### 2026-04-12 — cc795b75
**Commit:** `cc795b75b80fce9ec723d7af1b51fe1d89bf0403`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/MasterIPadView.jsx (NEW)
- src/components/ipad/WelcomeScreen.jsx (NEW)
- src/pages/StudioController.jsx (NEW)

---

### 2026-04-12 — e9c7dad7
**Commit:** `e9c7dad7b6382d255dcaa79c6864ada1af6cff31`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/admin/QuickActionsDropdown.jsx (NEW)
- src/components/dashboard/DashboardMetricCard.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-12 — dc5b801f
**Commit:** `dc5b801f9bbc0f3ad91f970ce659b8a8a5aa569c`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/ipad/WelcomeScreen.jsx (NEW)
- src/pages/AdminiPadController.jsx (NEW)
- src/pages/StudioController.jsx (NEW)

---

### 2026-04-11 — 1aec1f99
**Commit:** `1aec1f99b66b04ecd17059309161e45bf7e777a7`  
**Message:** File changes  
**Classification:** 1× MODIFIED  

**Files:**
- tailwind.config.js (MODIFIED)

---

### 2026-04-11 — 3f83184f
**Commit:** `3f83184f91b4ab6e852e2bcc4b9237b86a3a172c`  
**Message:** File changes  
**Classification:** 6× NEW, 1× MODIFIED  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/components/dashboard/DashboardMetricCard.jsx (NEW)
- src/components/dashboard/FloatingDayPanel.jsx (NEW)
- src/components/dashboard/SessionTimelineCard.jsx (NEW)
- src/hooks/useTheme.js (NEW)
- src/index.css (NEW)
- tailwind.config.js (MODIFIED)

---

### 2026-04-11 — 0e0a4d29
**Commit:** `0e0a4d2977b02b9e0e2b7703a6fa5d216172ef53`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/StudioController.jsx (NEW)

---

### 2026-04-11 — 7e2cf42d
**Commit:** `7e2cf42d2b848cc0701c27b5bf19bca5f023ace5`  
**Message:** File changes  
**Classification:** 4× NEW, 2× MODIFIED  

**Files:**
- src/components/ipad/DemoScreen.jsx (NEW)
- src/components/ipad/IdleScreen.jsx (NEW)
- src/pages/AdminiPadController.jsx (NEW)
- src/pages/StudioController.jsx (NEW)
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)

---

### 2026-04-11 — ca56f4c8
**Commit:** `ca56f4c8408cc98b7f351cf33a29d0ccb11fd51a`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/components/dashboard/DashboardMetricCard.jsx (NEW)
- src/hooks/useTheme.js (NEW)

---

### 2026-04-11 — 7bd3f848
**Commit:** `7bd3f84826df6d0d27d9e3453556763266f6145e`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/LightingPanel.jsx (NEW)
- src/pages/StudioController.jsx (NEW)

---

### 2026-04-11 — 5756d26d
**Commit:** `5756d26deafaed42b9568bf9599c2041cf8bde44`  
**Message:** File changes  
**Classification:** 2× NEW, 1× MODIFIED  

**Files:**
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/pages/AdminiPadController.jsx (NEW)
- base44/entities/iPadSession.jsonc (MODIFIED)

---

### 2026-04-11 — b3b4a959
**Commit:** `b3b4a959f93f24b22ff5570d22bfd34f7cf5a7bf`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/index.css (NEW)

---

### 2026-04-11 — 442a4aa6
**Commit:** `442a4aa6fd20a437134e2c4efd820733ff556cb2`  
**Message:** File changes  
**Classification:** 3× NEW, 1× CONFLICT  

**Files:**
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/hooks/useTheme.js (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — d4df16bd
**Commit:** `d4df16bd215b222c929d234467a3dbefbe039f07`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/dashboard/FloatingEventPanel.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)

---

### 2026-04-11 — d37f5413
**Commit:** `d37f5413563affbbed94992addb58b64125adcb0`  
**Message:** File changes  
**Classification:** 4× NEW, 1× CONFLICT  

**Files:**
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/components/AdminLayout.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/hooks/useTheme.js (NEW)

---

### 2026-04-11 — 981bd655
**Commit:** `981bd65522efbfc84fbdcf1941d47c18993becc6`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/CustomLogin.jsx (NEW)

---

### 2026-04-11 — 3a1682a1
**Commit:** `3a1682a1fefffdc5826186363751d43dfa46464d`  
**Message:** File changes  
**Classification:** 2× NEW, 4× MODIFIED  

**Files:**
- src/pages/AdminiPadController.jsx (NEW)
- src/pages/StudioController.jsx (NEW)
- base44/entities/iPadCommand.jsonc (MODIFIED)
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/iPadVersionControl/entry.ts (MODIFIED)
- index.html (MODIFIED)

---

### 2026-04-11 — 18612a7d
**Commit:** `18612a7d50b178d093fa8126aef26915702c760a`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (NEW)

---

### 2026-04-11 — ad879b0b
**Commit:** `ad879b0b49a934ac4115c07661c78b8fe3ba6cc3`  
**Message:** File changes  
**Classification:** 6× NEW, 1× MODIFIED  

**Files:**
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/components/ipad/CircularThermostat.jsx (NEW)
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/LightingCanvas.jsx (NEW)
- src/components/ipad/MasterIPadView.jsx (NEW)
- src/pages/StudioController.jsx (NEW)
- base44/entities/RoomLightingLayout.jsonc (MODIFIED)

---

### 2026-04-11 — ae210dd2
**Commit:** `ae210dd267db37ea0eb18787277cd0b8726c153b`  
**Message:** File changes  
**Classification:** 4× NEW, 1× CONFLICT  

**Files:**
- src/components/ui/FloatingPanel.jsx (CONFLICT)
- src/components/Sidebar.jsx (NEW)
- src/components/admin/QuickActionsDropdown.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — 1c572b9d
**Commit:** `1c572b9df1e37f5a5fc5d80a96f6d81e9fdfd6dc`  
**Message:** File changes  
**Classification:** 6× NEW, 2× MODIFIED  

**Files:**
- src/components/ipad/BackgroundLayer.jsx (NEW)
- src/components/ipad/CircularThermostat.jsx (NEW)
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/WelcomeScreen.jsx (NEW)
- src/pages/AdminiPadController.jsx (NEW)
- src/pages/StudioController.jsx (NEW)
- base44/entities/iPadSession.jsonc (MODIFIED)
- base44/functions/getIPadSession/entry.ts (MODIFIED)

---

### 2026-04-11 — c2e86504
**Commit:** `c2e8650418eebbc1a50d5c2ebb6839ce2adeed49`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/admin/AdminTopbar.jsx (NEW)
- src/components/admin/QuickActionsDropdown.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — 9098ede4
**Commit:** `9098ede4984a7a07e7d8e0cfd8577d4a7008ee96`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/WelcomeScreen.jsx (NEW)

---

### 2026-04-11 — c323e33f
**Commit:** `c323e33f986baffd4591304bb829aa07780e3cf1`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)

---

### 2026-04-11 — a32f6aaf
**Commit:** `a32f6aaf5c651c5fb4e0a9cfd0da3d058e619456`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)

---

### 2026-04-11 — 405ff264
**Commit:** `405ff2645dfa9116f45a10604c94db9f9720ab3c`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/hooks/useTheme.js (NEW)

---

### 2026-04-11 — d6bc2b03
**Commit:** `d6bc2b0353bf18864fc557c5844b5929794e7a66`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/CustomLogin.jsx (NEW)

---

### 2026-04-11 — e90d8ade
**Commit:** `e90d8ade0095f11aab3906ad29ec3d354bda70ff`  
**Message:** File changes  
**Classification:** 3× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)
- src/hooks/useTheme.js (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — eaa2d605
**Commit:** `eaa2d605c561c8ca2b8907bdc283bdff2e5785e7`  
**Message:** File changes  
**Classification:** 1× NEW, 1× MODIFIED  

**Files:**
- src/components/ipad/InSessionScreen.jsx (NEW)
- base44/functions/updateiPadStates/entry.ts (MODIFIED)

---

### 2026-04-11 — 133e1a47
**Commit:** `133e1a47a80afde1dd94e66a2a0f35c11efadfe9`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/AdminWorkflowMap.jsx (NEW)

---

### 2026-04-11 — 45df4805
**Commit:** `45df4805b47405ba1e7a9a233cd7efdffb6dfe73`  
**Message:** File changes  
**Classification:** 6× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/admin/AdminTopbar.jsx (NEW)
- src/components/admin/QuickActionsDropdown.jsx (NEW)
- src/hooks/useTheme.js (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — b70252c3
**Commit:** `b70252c38222938b0f63aff5a69088e429799ef8`  
**Message:** File changes  
**Classification:** 7× NEW  

**Files:**
- src/components/dashboard/DashboardMetricCard.jsx (NEW)
- src/components/dashboard/DashboardSectionCard.jsx (NEW)
- src/components/dashboard/FloatingDayPanel.jsx (NEW)
- src/components/dashboard/PremiumCalendar.jsx (NEW)
- src/components/dashboard/QuickActionButton.jsx (NEW)
- src/components/dashboard/SessionTimelineCard.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-11 — b639797b
**Commit:** `b639797b5b976543eb92bd7556598cb663e73edc`  
**Message:** File changes  
**Classification:** 5× NEW, 1× MODIFIED  

**Files:**
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/hooks/useTheme.js (NEW)
- src/pages/AdminNotifications.jsx (NEW)
- src/pages/AdminiPadController.jsx (NEW)
- base44/functions/updateiPadStates/entry.ts (MODIFIED)

---

### 2026-04-11 — ab283f49
**Commit:** `ab283f4946be1169715713f7ce6d97e71a73ed7e`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/lib/workflow-data.js (NEW)
- src/pages/AdminWorkflowMap.jsx (NEW)

---

### 2026-04-11 — 8f1d1755
**Commit:** `8f1d1755fdf2625f3500e6111a7f35f065251d44`  
**Message:** File changes  
**Classification:** 1× CONFLICT  

**Files:**
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)

---

### 2026-04-11 — 7ee5ce48
**Commit:** `7ee5ce489339e23c7fd33295626cf08acea8bb4f`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/lib/workflow-data.js (NEW)
- src/pages/AdminWorkflowMap.jsx (NEW)

---

### 2026-04-10 — b46081c2
**Commit:** `b46081c28e27e0923e6a8e83fc3b86c40007f948`  
**Message:** File changes  
**Classification:** 2× NEW, 1× CONFLICT  

**Files:**
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/dashboard/CalendarEventDrawer.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)

---

### 2026-04-09 — af66b4d8
**Commit:** `af66b4d869dab8de0123aa95d9d2811689867ef8`  
**Message:** File changes  
**Classification:** 5× MODIFIED  

**Files:**
- base44/functions/googleCalendarManager/entry.ts (MODIFIED)
- base44/functions/listCalendarEvents/entry.ts (MODIFIED)
- base44/functions/onBookingConfirmed/entry.ts (MODIFIED)
- base44/functions/syncBookingToGoogleCalendar/entry.ts (MODIFIED)
- base44/functions/syncGoogleCalendarToPortal/entry.ts (MODIFIED)

---

### 2026-04-09 — bdaef470
**Commit:** `bdaef4707a9511c2ad148b4ec372fd0764291a3c`  
**Message:** File changes  
**Classification:** 1× NEW, 3× MODIFIED  

**Files:**
- src/components/invoicing/InvoiceDrawer.jsx (NEW)
- base44/entities/Invoice.jsonc (MODIFIED)
- base44/functions/syncBookingToGoogleCalendar/entry.ts (MODIFIED)
- base44/functions/updateInvoice/entry.ts (MODIFIED)

---

### 2026-04-09 — 03b26f03
**Commit:** `03b26f0382257133014a0ddde27ff5b917147daf`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/booking/MultiDayRangePicker.jsx (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)

---

### 2026-04-09 — ef48c131
**Commit:** `ef48c1311f32c2e452356aab8796d3c0bbf371b0`  
**Message:** File changes  
**Classification:** 5× NEW, 1× MODIFIED  

**Files:**
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/shared-calendar/EventModal.jsx (NEW)
- src/pages/AdminSharedCalendarSettings.jsx (NEW)
- src/pages/SharedCalendar.jsx (NEW)
- base44/entities/SharedCalendarToken.jsonc (MODIFIED)

---

### 2026-04-09 — eb1d245d
**Commit:** `eb1d245da917a69a77eba835424aa68c57d69e78`  
**Message:** File changes  
**Classification:** 2× NEW, 1× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/lib/multi-day-pricing.js (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)

---

### 2026-04-09 — 1e437a1c
**Commit:** `1e437a1c6fd68062542e2075dde3be6f064f5ec0`  
**Message:** File changes  
**Classification:** 4× NEW, 1× MODIFIED  

**Files:**
- src/components/booking/BookingStepFooter.jsx (NEW)
- src/components/booking/MultiDayPricingEditor.jsx (NEW)
- src/components/booking/MultiDayRangePicker.jsx (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)
- base44/entities/Booking.jsonc (MODIFIED)

---

### 2026-04-08 — 7430e452
**Commit:** `7430e4525516a29ed8033626ef7a66fa3faa3fe7`  
**Message:** File changes  
**Classification:** 5× NEW  

**Files:**
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/bookings/BookingsCalendarView.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminCalendarSync.jsx (NEW)

---

### 2026-04-08 — 8935efc2
**Commit:** `8935efc2965480fc0399edb05c259bd142d33e7c`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/AdminRoomEditor.jsx (NEW)
- src/components/RoomForm/AddOnsSection.jsx (NEW)
- src/components/RoomForm/SettingsSection.jsx (NEW)
- src/pages/AdminRooms.jsx (NEW)

---

### 2026-04-08 — 2b9498c0
**Commit:** `2b9498c00d4a4fa2a4db44f9e822b814fc7d16be`  
**Message:** File changes  
**Classification:** 4× NEW, 2× CONFLICT  

**Files:**
- src/components/marketing/RoomOperatingHoursDisplay.jsx (CONFLICT)
- src/pages/RoomProfile.jsx (CONFLICT)
- src/components/AdminRoomEditor.jsx (NEW)
- src/lib/multi-day-pricing.js (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)
- src/pages/AdminOperatingHours.jsx (NEW)

---

### 2026-04-07 — d34c0954
**Commit:** `d34c095469b3a32fced1bcfbababae196b079ab1`  
**Message:** File changes  
**Classification:** 1× NEW, 1× MODIFIED  

**Files:**
- src/QA_BOOKING_AUDIT_REAL.md (NEW)
- base44/functions/getRoomAvailability/entry.ts (MODIFIED)

---

### 2026-04-07 — 6667830e
**Commit:** `6667830e0479cc3f26cc46c82256731d9574d15c`  
**Message:** File changes  
**Classification:** 4× NEW, 1× MODIFIED, 1× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/BOOKING_AVAILABILITY_FIX_QA.md (NEW)
- src/BOOKING_AVAILABILITY_FIX_SUMMARY.md (NEW)
- src/components/booking/UnifiedBookingDateTime.jsx (NEW)
- src/lib/availability-validation.js (NEW)
- base44/functions/getRoomAvailability/entry.ts (MODIFIED)

---

### 2026-04-07 — f0d8bd50
**Commit:** `f0d8bd501d70c3d20c8b390e195682ac709f7fc6`  
**Message:** File changes  
**Classification:** 6× NEW, 1× CONFLICT  

**Files:**
- src/components/RoomForm/RoomStudioPreview.jsx (CONFLICT)
- src/STUDIO_EDIT_REDESIGN_REPORT.md (NEW)
- src/components/AdminRoomEditor.jsx (NEW)
- src/components/RoomForm/AddOnsSection.jsx (NEW)
- src/components/RoomForm/BasicInfoSection.jsx (NEW)
- src/components/RoomForm/PricingSection.jsx (NEW)
- src/components/RoomForm/SettingsSection.jsx (NEW)

---

### 2026-04-07 — 252350b4
**Commit:** `252350b4da3c79bddc4395965ffe078c4a45979b`  
**Message:** File changes  
**Classification:** 8× NEW, 4× MODIFIED  

**Files:**
- src/AUTH_QA_TEST_REPORT.md (NEW)
- src/COMPLETE_AUTH_SYSTEM_SUMMARY.md (NEW)
- src/DEPLOYMENT_CHECKLIST.md (NEW)
- src/IMPLEMENTATION_SUMMARY.md (NEW)
- src/QA_TEST_SCENARIOS.md (NEW)
- src/SYSTEM_ARCHITECTURE.md (NEW)
- src/components/EnhancedInviteDrawer.jsx (NEW)
- src/components/admin/InviteManagementPanel.jsx (NEW)
- base44/functions/auditClientAuthFlow/entry.ts (MODIFIED)
- base44/functions/getClientAuthStatus/entry.ts (MODIFIED)
- base44/functions/manageInvites/entry.ts (MODIFIED)
- base44/functions/sendVerificationEmail/entry.ts (MODIFIED)

---

### 2026-04-07 — 5e843f15
**Commit:** `5e843f1509b8cc0d161cd6c8f0448621c96e9d23`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/App.jsx (NEW)

---

### 2026-04-07 — 2313cac0
**Commit:** `2313cac0ff58405119c5cacf374a403d458208f8`  
**Message:** File changes  
**Classification:** 5× NEW  

**Files:**
- src/components/AdminRoomEditor.jsx (NEW)
- src/components/RoomForm/AddOnsSection.jsx (NEW)
- src/components/RoomForm/BasicInfoSection.jsx (NEW)
- src/components/RoomForm/SettingsSection.jsx (NEW)
- src/pages/EmailVerification.jsx (NEW)

---

### 2026-04-07 — 56404a84
**Commit:** `56404a84ba65b25ed5a6e0d1adc00d83b788a526`  
**Message:** File changes  
**Classification:** 3× NEW, 2× MODIFIED, 1× CONFLICT  

**Files:**
- src/pages/Register.jsx (CONFLICT)
- src/App.jsx (NEW)
- src/components/InviteDrawer.jsx (NEW)
- src/pages/EmailVerification.jsx (NEW)
- base44/entities/Invite.jsonc (MODIFIED)
- base44/functions/sendClientInvite/entry.ts (MODIFIED)

---

### 2026-04-07 — 6325a206
**Commit:** `6325a206aeddbee7078f18bd6f576a154e86617d`  
**Message:** File changes  
**Classification:** 5× NEW, 2× MODIFIED, 1× CONFLICT  

**Files:**
- src/pages/Register.jsx (CONFLICT)
- src/App.jsx (NEW)
- src/components/admin/InviteStatusPanel.jsx (NEW)
- src/pages/AdminClientProfile.jsx (NEW)
- src/pages/AdminClients.jsx (NEW)
- src/pages/EmailVerification.jsx (NEW)
- base44/entities/Client.jsonc (MODIFIED)
- base44/functions/sendClientInvite/entry.ts (MODIFIED)

---

### 2026-04-07 — 636761a9
**Commit:** `636761a93370768dc6010d2d809bae38ae0aa70c`  
**Message:** File changes  
**Classification:** 5× NEW, 3× MODIFIED  

**Files:**
- src/components/client/CompliancePanel.jsx (NEW)
- src/components/client/GuestListPanel.jsx (NEW)
- src/pages/AdminClientProfile.jsx (NEW)
- src/pages/ClientBookingHistory.jsx (NEW)
- src/pages/ClientDashboard.jsx (NEW)
- base44/entities/BookingGuestList.jsonc (MODIFIED)
- base44/entities/ClientComplianceRecord.jsonc (MODIFIED)
- base44/functions/parseDocumentPDF/entry.ts (MODIFIED)

---

### 2026-04-07 — 676dc161
**Commit:** `676dc1610f05128b89fa0126e69d23c20704faba`  
**Message:** File changes  
**Classification:** 4× NEW, 1× CONFLICT  

**Files:**
- src/components/RoomForm/WebsitePreviewCard.jsx (CONFLICT)
- src/components/AdminRoomEditor.jsx (NEW)
- src/components/RoomForm/AddOnsSection.jsx (NEW)
- src/components/RoomForm/PricingAdvisorPanel.jsx (NEW)
- src/components/RoomForm/RoomHoursSection.jsx (NEW)

---

### 2026-04-07 — 1862d0c7
**Commit:** `1862d0c7d8ed4d95a5558fc1d25c08310b458f7f`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/admin/OperatingHoursGrid.jsx (NEW)
- src/pages/AdminOperatingHours.jsx (NEW)

---

### 2026-04-07 — 313aca7f
**Commit:** `313aca7f61a624c87f188c98f4b6aaae10895e71`  
**Message:** File changes  
**Classification:** 5× NEW  

**Files:**
- src/App.jsx (NEW)
- src/components/agreements/AICreationModal.jsx (NEW)
- src/components/agreements/AgreementEditor.jsx (NEW)
- src/components/agreements/AgreementList.jsx (NEW)
- src/pages/AdminAgreements.jsx (NEW)

---

### 2026-04-07 — 61e218eb
**Commit:** `61e218eb466739aae99da2d06ae3acd69d0180e8`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/AdminMarketingMedia.jsx (NEW)

---

### 2026-04-07 — 56830b4d
**Commit:** `56830b4d1b374ed0e2faf19fce574f7e2dd290ca`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/pages/AdminMarketingMedia.jsx (NEW)

---

### 2026-04-07 — 0208c32e
**Commit:** `0208c32ed85738e150001c25d5a7f66a947ffec7`  
**Message:** File changes  
**Classification:** 4× NEW, 1× MODIFIED, 3× CONFLICT  

**Files:**
- src/components/MarketingFooter.jsx (CONFLICT)
- src/pages/DynamicCreditsPage.jsx (CONFLICT)
- src/pages/DynamicMembershipsPage.jsx (CONFLICT)
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/pages/About.jsx (NEW)
- src/pages/AdminSocialLinks.jsx (NEW)
- base44/entities/AppSetting.jsonc (MODIFIED)

---

### 2026-04-07 — 2263821f
**Commit:** `2263821f0a68a65a983987e5ba51f1f37add7f9d`  
**Message:** File changes  
**Classification:** 5× NEW, 1× MODIFIED  

**Files:**
- src/App.jsx (NEW)
- src/components/admin/OperatingHoursGrid.jsx (NEW)
- src/pages/AdminBranding.jsx (NEW)
- src/pages/AdminEmailDesigns.jsx (NEW)
- src/pages/AdminOperatingHours.jsx (NEW)
- base44/entities/OperatingHours.jsonc (MODIFIED)

---

### 2026-04-07 — 0fcbeb00
**Commit:** `0fcbeb007b00097a9308821a3ed111ea0670c8bf`  
**Message:** File changes  
**Classification:** 4× NEW, 5× MODIFIED  

**Files:**
- src/App.jsx (NEW)
- src/components/BookingDetailDrawer.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/pages/AdminSyncQueue.jsx (NEW)
- base44/entities/SyncReviewItem.jsonc (MODIFIED)
- base44/functions/approveSyncItem/entry.ts (MODIFIED)
- base44/functions/processGoogleSyncEvents/entry.ts (MODIFIED)
- base44/functions/syncBookingToGoogleCalendar/entry.ts (MODIFIED)
- base44/functions/syncGoogleCalendarToPortal/entry.ts (MODIFIED)

---

### 2026-04-07 — e174e925
**Commit:** `e174e925fdf29ab5b513003f9a04b8326ad35f30`  
**Message:** File changes  
**Classification:** 7× NEW, 1× MODIFIED, 1× CONFLICT  

**Files:**
- src/pages/Studios.jsx (CONFLICT)
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/pages/About.jsx (NEW)
- src/pages/AdminAgreements.jsx (NEW)
- src/pages/AdminCampaigns.jsx (NEW)
- src/pages/AdminEmailDesigns.jsx (NEW)
- src/pages/Contact.jsx (NEW)
- base44/entities/EmailCampaign.jsonc (MODIFIED)

---

### 2026-04-07 — 0aa884ad
**Commit:** `0aa884adb0ea2f30e84fb60b5eb0655110bd9f2e`  
**Message:** File changes  
**Classification:** 7× NEW, 1× MODIFIED, 2× CONFLICT  

**Files:**
- src/pages/Landing.jsx (CONFLICT)
- src/pages/Studios.jsx (CONFLICT)
- src/App.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/marketing/StudioTourCTA.jsx (NEW)
- src/hooks/useMarketingMedia.js (NEW)
- src/pages/About.jsx (NEW)
- src/pages/AdminMarketingMedia.jsx (NEW)
- src/pages/Contact.jsx (NEW)
- base44/entities/MarketingMedia.jsonc (MODIFIED)

---

### 2026-04-07 — 72c94f41
**Commit:** `72c94f41bb1503ed2ebf0597c9590b0b905e8453`  
**Message:** File changes  
**Classification:** 7× NEW, 2× MODIFIED, 1× CONFLICT  

**Files:**
- src/components/booking/BookingDateTimeStep.jsx (CONFLICT)
- src/components/AdminRoomEditor.jsx (NEW)
- src/components/BookingFlowSteps.jsx (NEW)
- src/components/RoomForm/PricingAdvisorPanel.jsx (NEW)
- src/components/RoomForm/PricingSection.jsx (NEW)
- src/components/booking/MultiDayRangePicker.jsx (NEW)
- src/lib/multi-day-pricing.js (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)
- base44/entities/Booking.jsonc (MODIFIED)
- base44/entities/Room.jsonc (MODIFIED)

---

### 2026-04-07 — c7f24226
**Commit:** `c7f2422624fb65a5baba753e172c8a6c060b293a`  
**Message:** File changes  
**Classification:** 8× NEW, 3× CONFLICT  

**Files:**
- src/components/booking/ClientSelectStep.jsx (CONFLICT)
- src/components/dashboard/MonthCalendar.jsx (CONFLICT)
- src/components/ui/TabBar.jsx (CONFLICT)
- src/components/Sidebar.jsx (NEW)
- src/pages/AdminBookNewSession.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)
- src/pages/AdminFinancialDashboard.jsx (NEW)
- src/pages/AdminIntegrations.jsx (NEW)
- src/pages/AdminInvoices.jsx (NEW)
- src/pages/AdminPricingDashboard.jsx (NEW)

---

### 2026-04-06 — 43b719b7
**Commit:** `43b719b79988519c14c5863cc39137677afc34f8`  
**Message:** File changes  
**Classification:** 8× NEW, 1× CONFLICT  

**Files:**
- src/components/ui/SegmentedControl.jsx (CONFLICT)
- src/components/AdminLayout.jsx (NEW)
- src/components/AdminSectionNav.jsx (NEW)
- src/components/PortalTopBar.jsx (NEW)
- src/components/financial/FinancialTabs.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminFinancialDashboard.jsx (NEW)
- src/pages/AdminInvoices.jsx (NEW)
- src/pages/AdminPricingDashboard.jsx (NEW)

---

### 2026-04-06 — d55de2be
**Commit:** `d55de2be68ae8842b7e6f3a9fdc7bd6eaa3e367d`  
**Message:** File changes  
**Classification:** 13× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/components/AdminSectionNav.jsx (NEW)
- src/components/Sidebar.jsx (NEW)
- src/components/dashboard/NativeCalendar.jsx (NEW)
- src/pages/AdminAgreements.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminClients.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)
- src/pages/AdminFinancialDashboard.jsx (NEW)
- src/pages/AdminForms.jsx (NEW)
- src/pages/AdminInvoices.jsx (NEW)
- src/pages/AdminPricingDashboard.jsx (NEW)
- src/pages/AdminSettings.jsx (NEW)

---

### 2026-04-06 — 8373550c
**Commit:** `8373550cc14ad567f3b4ae8e4f7eef017a1468b4`  
**Message:** File changes  
**Classification:** 6× NEW, 6× CONFLICT  

**Files:**
- src/components/ui/EmptyState.jsx (CONFLICT)
- src/components/ui/FilterPills.jsx (CONFLICT)
- src/components/ui/PortalTable.jsx (CONFLICT)
- src/components/ui/SearchInput.jsx (CONFLICT)
- src/components/ui/SettingCard.jsx (CONFLICT)
- src/components/ui/Spinner.jsx (CONFLICT)
- src/lib/status-styles.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminClients.jsx (NEW)
- src/pages/AdminFinancialDashboard.jsx (NEW)
- src/pages/AdminInvoices.jsx (NEW)
- src/pages/AdminSettings.jsx (NEW)

---

### 2026-04-06 — efc55f0b
**Commit:** `efc55f0bb74d4d56a9b6fe39053207cd6fea7944`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/components/Sidebar.jsx (NEW)

---

### 2026-04-06 — d4afd2f3
**Commit:** `d4afd2f3c3900b58a773c28ed22fe295c0026753`  
**Message:** File changes  
**Classification:** 3× NEW, 4× MODIFIED  

**Files:**
- src/components/dashboard/MasterCalendarEmbed.jsx (NEW)
- src/pages/AdminBranding.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)
- base44/entities/AppSetting.jsonc (MODIFIED)
- base44/entities/Booking.jsonc (MODIFIED)
- base44/functions/syncBookingToGoogleCalendar/entry.ts (MODIFIED)
- base44/functions/syncGoogleCalendarToPortal/entry.ts (MODIFIED)

---

### 2026-04-06 — 55794f47
**Commit:** `55794f4732a4cd667da8e0d098f96aeb3591d94a`  
**Message:** File changes  
**Classification:** 1× NEW  

**Files:**
- src/pages/AdminBranding.jsx (NEW)

---

### 2026-04-06 — 9ad09a8d
**Commit:** `9ad09a8d1fd0b0a2fd026f493e702e3641171e00`  
**Message:** File changes  
**Classification:** 9× NEW  

**Files:**
- src/pages/AdminAddOns.jsx (NEW)
- src/pages/AdminBranding.jsx (NEW)
- src/pages/AdminDashboard.jsx (NEW)
- src/pages/AdminEmailDesigns.jsx (NEW)
- src/pages/AdminInvoices.jsx (NEW)
- src/pages/AdminPortalSettings.jsx (NEW)
- src/pages/AdminPricingDashboard.jsx (NEW)
- src/pages/AdminRooms.jsx (NEW)
- src/pages/AdminSettings.jsx (NEW)

---

### 2026-04-06 — 0f0833bf
**Commit:** `0f0833bfaf11bf264a12debe01c8b248d68eb651`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/PortalTopBar.jsx (NEW)
- src/pages/AdminBookingsManager.jsx (NEW)
- src/pages/AdminClients.jsx (NEW)
- src/pages/AdminPricing.jsx (NEW)

---

### 2026-04-06 — 08460b39
**Commit:** `08460b399ab905a1a1d8ec7c53793e0ec9679007`  
**Message:** File changes  
**Classification:** 2× NEW  

**Files:**
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/LightingPanel.jsx (NEW)

---

### 2026-04-06 — 86755ec2
**Commit:** `86755ec2b6da5d09067c2bf224e86d7a2e45c0dd`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/ipad/ClimateDetailPanel.jsx (NEW)
- src/components/ipad/HelpSupportPanel.jsx (NEW)
- src/components/ipad/InSessionScreen.jsx (NEW)
- src/components/ipad/LightingPanel.jsx (NEW)

---

### 2026-04-04 — abdad2a2
**Commit:** `abdad2a2f22f60ac0d7ad5c73c34f0c02a4ddfcf`  
**Message:** File changes  
**Classification:** 4× NEW  

**Files:**
- src/components/AdminLayout.jsx (NEW)
- src/components/PortalTopBar.jsx (NEW)
- src/pages/AdminAccessControl.jsx (NEW)
- src/pages/AdminUsers.jsx (NEW)

---


### dcb2a8e
**Date:** 2026-04-22 15:33 UTC
**Commit:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35
**Classification:**
- NEW: 3 file(s)
  - project.config.json
  - public/_redirects
  - scripts/deploy-guard.mjs
- MODIFIED: 1 file(s)
  - package.json
- CONFLICT (Claude Code): 31 file(s)
  - src/components/MarketingFooter.jsx
  - src/components/MarketingHeader.jsx
  - src/components/RoomForm/RoomStudioPreview.jsx
  - src/components/RoomForm/WebsitePreviewCard.jsx
  - src/components/booking/BookingDateTimeStep.jsx
  - ... +26 more


### aa4661f
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6
**Classification:**
- CONFLICT (Claude Code): 6 file(s)
  - src/pages/DynamicCreditsPage.jsx
  - src/pages/DynamicMembershipsPage.jsx
  - src/pages/GuestBuyCredits.jsx
  - src/pages/MembershipSignup.jsx
  - src/pages/Register.jsx
  - ... +1 more


### f19cdf0
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4
**Classification:**
- CONFLICT (Claude Code): 4 file(s)
  - src/pages/Landing.jsx
  - src/pages/RoomProfile.jsx
  - src/pages/Services.jsx
  - src/pages/Studios.jsx


### 22cdea7
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1
**Classification:**
- CONFLICT (Claude Code): 1 file(s)
  - src/pages/BookingFlow.jsx


### 3885333
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3
**Classification:**
- CONFLICT (Claude Code): 3 file(s)
  - src/components/dashboard/MonthCalendar.jsx
  - src/components/ipad/FiveMinWarning.jsx
  - src/components/ipad/ThankYouScreen.jsx


### 3564003
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2
**Classification:**
- CONFLICT (Claude Code): 2 file(s)
  - src/components/RoomForm/RoomStudioPreview.jsx
  - src/components/RoomForm/WebsitePreviewCard.jsx


### 923b30e
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3
**Classification:**
- CONFLICT (Claude Code): 3 file(s)
  - src/components/MarketingFooter.jsx
  - src/components/MarketingHeader.jsx
  - src/components/marketing/RoomOperatingHoursDisplay.jsx


### 18e25d2
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: booking components — refined versions from Claude Code
**Files changed:** 2
**Classification:**
- CONFLICT (Claude Code): 2 file(s)
  - src/components/booking/BookingDateTimeStep.jsx
  - src/components/booking/ClientSelectStep.jsx


### 762ca5e
**Date:** 2026-04-22 05:04 UTC
**Commit:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10
**Classification:**
- CONFLICT (Claude Code): 10 file(s)
  - src/components/ui/EmptyState.jsx
  - src/components/ui/FilterPills.jsx
  - src/components/ui/PortalDrawer.jsx
  - src/components/ui/PortalTable.jsx
  - src/components/ui/SearchInput.jsx
  - ... +5 more


### 47b2dd6
**Date:** 2026-04-20 04:07 UTC
**Commit:** feat: move design site to cloudflare pages
**Files changed:** 4
**Classification:**
- NEW: 3 file(s)
  - project.config.json
  - public/_redirects
  - scripts/deploy-guard.mjs
- MODIFIED: 1 file(s)
  - package.json

### 47b2dd6 | 2026-04-20
**Message:** feat: move design site to cloudflare pages
**Files:** 3× NEW, 1× MODIFIED
**NEW files:** project.config.json, public/_redirects, scripts/deploy-guard.mjs

### 762ca5e | 2026-04-22
**Message:** sync: UI primitives — refined versions from Claude Code
**Files:** 10× CONFLICT
**CONFLICT files:** src/components/ui/EmptyState.jsx, src/components/ui/FilterPills.jsx, src/components/ui/PortalDrawer.jsx, src/components/ui/PortalTable.jsx, src/components/ui/SearchInput.jsx, src/components/ui/SegmentedControl.jsx, src/components/ui/SettingCard.jsx, src/components/ui/Spinner.jsx, src/components/ui/TabBar.jsx, src/components/ui/button.jsx

### 18e25d2 | 2026-04-22
**Message:** sync: booking components — refined versions from Claude Code
**Files:** 2× CONFLICT
**CONFLICT files:** src/components/booking/BookingDateTimeStep.jsx, src/components/booking/ClientSelectStep.jsx

### 923b30e | 2026-04-22
**Message:** sync: marketing components — refined versions from Claude Code
**Files:** 3× CONFLICT
**CONFLICT files:** src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/marketing/RoomOperatingHoursDisplay.jsx

### 3564003 | 2026-04-22
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files:** 2× CONFLICT
**CONFLICT files:** src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx

### 3885333 | 2026-04-22
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files:** 3× CONFLICT
**CONFLICT files:** src/components/dashboard/MonthCalendar.jsx, src/components/ipad/FiveMinWarning.jsx, src/components/ipad/ThankYouScreen.jsx

### 22cdea7 | 2026-04-22
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files:** 1× CONFLICT
**CONFLICT files:** src/pages/BookingFlow.jsx

### f19cdf0 | 2026-04-22
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files:** 4× CONFLICT
**CONFLICT files:** src/pages/Landing.jsx, src/pages/RoomProfile.jsx, src/pages/Services.jsx, src/pages/Studios.jsx

### aa4661f | 2026-04-22
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files:** 6× CONFLICT
**CONFLICT files:** src/pages/DynamicCreditsPage.jsx, src/pages/DynamicMembershipsPage.jsx, src/pages/GuestBuyCredits.jsx, src/pages/MembershipSignup.jsx, src/pages/Register.jsx, src/pages/UnifiedCheckout.jsx

### dcb2a8e | 2026-04-22
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files:** 31× CONFLICT, 3× NEW, 1× MODIFIED
**CONFLICT files:** src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx, src/components/booking/BookingDateTimeStep.jsx, src/components/booking/ClientSelectStep.jsx, src/components/dashboard/MonthCalendar.jsx, src/components/ipad/FiveMinWarning.jsx, src/components/ipad/ThankYouScreen.jsx, src/components/marketing/RoomOperatingHoursDisplay.jsx, src/components/ui/EmptyState.jsx, src/components/ui/FilterPills.jsx, src/components/ui/PortalDrawer.jsx, src/components/ui/PortalTable.jsx, src/components/ui/SearchInput.jsx, src/components/ui/SegmentedControl.jsx, src/components/ui/SettingCard.jsx, src/components/ui/Spinner.jsx, src/components/ui/TabBar.jsx, src/components/ui/button.jsx, src/pages/BookingFlow.jsx, src/pages/DynamicCreditsPage.jsx, src/pages/DynamicMembershipsPage.jsx, src/pages/GuestBuyCredits.jsx, src/pages/Landing.jsx, src/pages/MembershipSignup.jsx, src/pages/Register.jsx, src/pages/RoomProfile.jsx, src/pages/Services.jsx, src/pages/Studios.jsx, src/pages/UnifiedCheckout.jsx
**NEW files:** project.config.json, public/_redirects, scripts/deploy-guard.mjs