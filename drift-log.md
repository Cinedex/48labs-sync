## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
**NEW:**
- `project.config.json`
- `public/_redirects`
- `scripts/deploy-guard.mjs`
**MODIFIED:**
- `package.json`
**CONFLICT:**
- `src/components/MarketingFooter.jsx`
- `src/components/MarketingHeader.jsx`
- `src/components/RoomForm/RoomStudioPreview.jsx`
- `src/components/RoomForm/WebsitePreviewCard.jsx`
- `src/components/booking/BookingDateTimeStep.jsx`
- `src/components/booking/ClientSelectStep.jsx`
- `src/components/dashboard/MonthCalendar.jsx`
- `src/components/ipad/FiveMinWarning.jsx`
- `src/components/ipad/ThankYouScreen.jsx`
- `src/components/marketing/RoomOperatingHoursDisplay.jsx`
- ... and 21 more
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (6× CONFLICT)
**CONFLICT:**
- `src/pages/DynamicCreditsPage.jsx`
- `src/pages/DynamicMembershipsPage.jsx`
- `src/pages/GuestBuyCredits.jsx`
- `src/pages/MembershipSignup.jsx`
- `src/pages/Register.jsx`
- `src/pages/UnifiedCheckout.jsx`
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (4× CONFLICT)
**CONFLICT:**
- `src/pages/Landing.jsx`
- `src/pages/RoomProfile.jsx`
- `src/pages/Services.jsx`
- `src/pages/Studios.jsx`
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (1× CONFLICT)
**CONFLICT:**
- `src/pages/BookingFlow.jsx`
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (3× CONFLICT)
**CONFLICT:**
- `src/components/dashboard/MonthCalendar.jsx`
- `src/components/ipad/FiveMinWarning.jsx`
- `src/components/ipad/ThankYouScreen.jsx`
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (2× CONFLICT)
**CONFLICT:**
- `src/components/RoomForm/RoomStudioPreview.jsx`
- `src/components/RoomForm/WebsitePreviewCard.jsx`
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (3× CONFLICT)
**CONFLICT:**
- `src/components/MarketingFooter.jsx`
- `src/components/MarketingHeader.jsx`
- `src/components/marketing/RoomOperatingHoursDisplay.jsx`
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (2× CONFLICT)
**CONFLICT:**
- `src/components/booking/BookingDateTimeStep.jsx`
- `src/components/booking/ClientSelectStep.jsx`
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (10× CONFLICT)
**CONFLICT:**
- `src/components/ui/EmptyState.jsx`
- `src/components/ui/FilterPills.jsx`
- `src/components/ui/PortalDrawer.jsx`
- `src/components/ui/PortalTable.jsx`
- `src/components/ui/SearchInput.jsx`
- `src/components/ui/SegmentedControl.jsx`
- `src/components/ui/SettingCard.jsx`
- `src/components/ui/Spinner.jsx`
- `src/components/ui/TabBar.jsx`
- `src/components/ui/button.jsx`
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED)
**NEW:**
- `project.config.json`
- `public/_redirects`
- `scripts/deploy-guard.mjs`
**MODIFIED:**
- `package.json`
---
## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED)
**NEW:**
- `src/components/ProtectedRoute.jsx`
**MODIFIED:**
- `package-lock.json`
- `package.json`
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `package-lock.json`
- `package.json`
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED)
**NEW:**
- `src/database/data-migration-plan.md`
- `src/database/migration-order.json`
**MODIFIED:**
- `src/database/MIGRATION_REPORT.md`
- `src/database/supabase/schema.sql`
- `src/database/types/schema.ts`
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/lib/workflow-data.js`
- `src/pages/AdminWorkflowMap.jsx`
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW)
**NEW:**
- `src/contracts/schema/enums.json`
- `src/contracts/schema/relationships.json`
- `src/contracts/schema/tables.json`
- `src/database/MIGRATION_REPORT.md`
- `src/database/mappings/base44-map.ts`
- `src/database/supabase/schema.sql`
- `src/database/types/schema.ts`
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (6× MODIFIED)
**MODIFIED:**
- `base44/entities/RoomLightingLayout.jsonc`
- `base44/entities/iPadCommand.jsonc`
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/LightingPanel.jsx`
- `src/components/ipad/MasterIPadView.jsx`
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (1× CONFLICT)
**CONFLICT:**
- `src/pages/Landing.jsx`
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/lib/workflow-data.js`
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/AdminWorkflowMap.jsx`
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `tailwind.config.js`
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (7× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/components/dashboard/FloatingDayPanel.jsx`
- `src/components/dashboard/SessionTimelineCard.jsx`
- `src/hooks/useTheme.js`
- `src/index.css`
- `tailwind.config.js`
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/StudioController.jsx`
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED)
**NEW:**
- `src/components/ipad/DemoScreen.jsx`
- `src/components/ipad/IdleScreen.jsx`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `base44/functions/getIPadSession/entry.ts`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/hooks/useTheme.js`
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/LightingPanel.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `src/components/ipad/InSessionScreen.jsx`
- `src/pages/AdminiPadController.jsx`
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/index.css`
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (3× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
- `src/pages/AdminDashboard.jsx`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED)
**NEW:**
- `src/components/dashboard/FloatingEventPanel.jsx`
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (4× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/CustomLogin.jsx`
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED)
**NEW:**
- `base44/entities/iPadCommand.jsonc`
- `base44/functions/iPadVersionControl/entry.ts`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `index.html`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED)
**NEW:**
- `base44/entities/RoomLightingLayout.jsonc`
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/components/ipad/CircularThermostat.jsx`
- `src/components/ipad/InSessionScreen.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (4× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED)
**NEW:**
- `src/components/ipad/BackgroundLayer.jsx`
- `src/components/ipad/CircularThermostat.jsx`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `base44/functions/getIPadSession/entry.ts`
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/admin/AdminTopbar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/CustomLogin.jsx`
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/hooks/useTheme.js`
- `src/pages/AdminDashboard.jsx`
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
**NEW:**
- `project.config.json`
- `public/_redirects`
- `scripts/deploy-guard.mjs`
**MODIFIED:**
- `package.json`
**CONFLICT:**
- `src/components/MarketingFooter.jsx`
- `src/components/MarketingHeader.jsx`
- `src/components/RoomForm/RoomStudioPreview.jsx`
- `src/components/RoomForm/WebsitePreviewCard.jsx`
- `src/components/booking/BookingDateTimeStep.jsx`
- `src/components/booking/ClientSelectStep.jsx`
- `src/components/dashboard/MonthCalendar.jsx`
- `src/components/ipad/FiveMinWarning.jsx`
- `src/components/ipad/ThankYouScreen.jsx`
- `src/components/marketing/RoomOperatingHoursDisplay.jsx`
- ... and 21 more
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (6× CONFLICT)
**CONFLICT:**
- `src/pages/DynamicCreditsPage.jsx`
- `src/pages/DynamicMembershipsPage.jsx`
- `src/pages/GuestBuyCredits.jsx`
- `src/pages/MembershipSignup.jsx`
- `src/pages/Register.jsx`
- `src/pages/UnifiedCheckout.jsx`
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (4× CONFLICT)
**CONFLICT:**
- `src/pages/Landing.jsx`
- `src/pages/RoomProfile.jsx`
- `src/pages/Services.jsx`
- `src/pages/Studios.jsx`
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (1× CONFLICT)
**CONFLICT:**
- `src/pages/BookingFlow.jsx`
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (3× CONFLICT)
**CONFLICT:**
- `src/components/dashboard/MonthCalendar.jsx`
- `src/components/ipad/FiveMinWarning.jsx`
- `src/components/ipad/ThankYouScreen.jsx`
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (2× CONFLICT)
**CONFLICT:**
- `src/components/RoomForm/RoomStudioPreview.jsx`
- `src/components/RoomForm/WebsitePreviewCard.jsx`
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (3× CONFLICT)
**CONFLICT:**
- `src/components/MarketingFooter.jsx`
- `src/components/MarketingHeader.jsx`
- `src/components/marketing/RoomOperatingHoursDisplay.jsx`
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (2× CONFLICT)
**CONFLICT:**
- `src/components/booking/BookingDateTimeStep.jsx`
- `src/components/booking/ClientSelectStep.jsx`
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (10× CONFLICT)
**CONFLICT:**
- `src/components/ui/EmptyState.jsx`
- `src/components/ui/FilterPills.jsx`
- `src/components/ui/PortalDrawer.jsx`
- `src/components/ui/PortalTable.jsx`
- `src/components/ui/SearchInput.jsx`
- `src/components/ui/SegmentedControl.jsx`
- `src/components/ui/SettingCard.jsx`
- `src/components/ui/Spinner.jsx`
- `src/components/ui/TabBar.jsx`
- `src/components/ui/button.jsx`
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED)
**NEW:**
- `project.config.json`
- `public/_redirects`
- `scripts/deploy-guard.mjs`
**MODIFIED:**
- `package.json`
---
## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED)
**NEW:**
- `src/components/ProtectedRoute.jsx`
**MODIFIED:**
- `package-lock.json`
- `package.json`
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `package-lock.json`
- `package.json`
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED)
**NEW:**
- `src/database/data-migration-plan.md`
- `src/database/migration-order.json`
**MODIFIED:**
- `src/database/MIGRATION_REPORT.md`
- `src/database/supabase/schema.sql`
- `src/database/types/schema.ts`
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/lib/workflow-data.js`
- `src/pages/AdminWorkflowMap.jsx`
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW)
**NEW:**
- `src/contracts/schema/enums.json`
- `src/contracts/schema/relationships.json`
- `src/contracts/schema/tables.json`
- `src/database/MIGRATION_REPORT.md`
- `src/database/mappings/base44-map.ts`
- `src/database/supabase/schema.sql`
- `src/database/types/schema.ts`
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (6× MODIFIED)
**MODIFIED:**
- `base44/entities/RoomLightingLayout.jsonc`
- `base44/entities/iPadCommand.jsonc`
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/LightingPanel.jsx`
- `src/components/ipad/MasterIPadView.jsx`
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (1× CONFLICT)
**CONFLICT:**
- `src/pages/Landing.jsx`
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/lib/workflow-data.js`
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/AdminTopbar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/AdminWorkflowMap.jsx`
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `tailwind.config.js`
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (7× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/components/dashboard/FloatingDayPanel.jsx`
- `src/components/dashboard/SessionTimelineCard.jsx`
- `src/hooks/useTheme.js`
- `src/index.css`
- `tailwind.config.js`
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/StudioController.jsx`
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED)
**NEW:**
- `src/components/ipad/DemoScreen.jsx`
- `src/components/ipad/IdleScreen.jsx`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `base44/functions/getIPadSession/entry.ts`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/dashboard/DashboardMetricCard.jsx`
- `src/hooks/useTheme.js`
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/LightingPanel.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `src/components/ipad/InSessionScreen.jsx`
- `src/pages/AdminiPadController.jsx`
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/index.css`
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (3× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
- `src/pages/AdminDashboard.jsx`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED)
**NEW:**
- `src/components/dashboard/FloatingEventPanel.jsx`
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (4× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/CustomLogin.jsx`
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED)
**NEW:**
- `base44/entities/iPadCommand.jsonc`
- `base44/functions/iPadVersionControl/entry.ts`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `index.html`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED)
**NEW:**
- `base44/entities/RoomLightingLayout.jsonc`
- `src/components/ipad/LightingCanvas.jsx`
- `src/components/ipad/MasterIPadView.jsx`
**MODIFIED:**
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/components/ipad/CircularThermostat.jsx`
- `src/components/ipad/InSessionScreen.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (4× MODIFIED | 1× CONFLICT)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
**CONFLICT:**
- `src/components/ui/FloatingPanel.jsx`
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED)
**NEW:**
- `src/components/ipad/BackgroundLayer.jsx`
- `src/components/ipad/CircularThermostat.jsx`
**MODIFIED:**
- `base44/entities/iPadSession.jsonc`
- `base44/functions/getIPadSession/entry.ts`
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
- `src/pages/AdminiPadController.jsx`
- `src/pages/StudioController.jsx`
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/admin/AdminTopbar.jsx`
- `src/components/admin/QuickActionsDropdown.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/pages/AdminDashboard.jsx`
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (2× MODIFIED)
**MODIFIED:**
- `src/components/ipad/InSessionScreen.jsx`
- `src/components/ipad/WelcomeScreen.jsx`
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (4× MODIFIED)
**MODIFIED:**
- `src/components/AdminLayout.jsx`
- `src/components/Sidebar.jsx`
- `src/components/dashboard/PremiumCalendar.jsx`
- `src/hooks/useTheme.js`
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (1× MODIFIED)
**MODIFIED:**
- `src/pages/CustomLogin.jsx`
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (3× MODIFIED)
**MODIFIED:**
- `src/components/Sidebar.jsx`
- `src/hooks/useTheme.js`
- `src/pages/AdminDashboard.jsx`
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW, 32× MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (6× MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (4× MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (1× MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (3× MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (2× MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (3× MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (2× MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (10× MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW, 1× MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---

## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (1× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (NEW)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---

## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---

## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---

## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---

## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---

## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---

## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
- `src/components/ProtectedRoute.jsx` (NEW)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (6× MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (4× MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (1× MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (3× MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (2× MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (3× MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (2× MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (10× MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---
## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
- `src/components/ProtectedRoute.jsx` (NEW)
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 0 (0× NEW | 0× MODIFIED | 0× CONFLICT)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---
## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
- `src/components/ProtectedRoute.jsx` (NEW)
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 files (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 files (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 files (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 files (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 files (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 files (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 files (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 files (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 files (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 files (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 files (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ProtectedRoute.jsx` (NEW)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 files (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 files (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---

## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 files (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 files (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 files (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---

## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 files (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 files (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---

## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---

## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 files (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 files (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 files (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 files (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 files (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---

## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---

## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 files (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 files (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 files (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 files (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 files (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 files (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 files (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 files (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 files (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---

## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 files (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 files (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 files (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
  \`package.json\` (MODIFIED)
  \`project.config.json\` (NEW)
  \`public/_redirects\` (NEW)
  \`scripts/deploy-guard.mjs\` (NEW)
  \`src/components/MarketingFooter.jsx\` (CONFLICT)
  \`src/components/MarketingHeader.jsx\` (CONFLICT)
  \`src/components/RoomForm/RoomStudioPreview.jsx\` (CONFLICT)
  \`src/components/RoomForm/WebsitePreviewCard.jsx\` (CONFLICT)
  \`src/components/booking/BookingDateTimeStep.jsx\` (CONFLICT)
  \`src/components/booking/ClientSelectStep.jsx\` (CONFLICT)
  \`src/components/dashboard/MonthCalendar.jsx\` (CONFLICT)
  \`src/components/ipad/FiveMinWarning.jsx\` (CONFLICT)
  \`src/components/ipad/ThankYouScreen.jsx\` (CONFLICT)
  \`src/components/marketing/RoomOperatingHoursDisplay.jsx\` (CONFLICT)
  \`src/components/ui/EmptyState.jsx\` (CONFLICT)
  \`src/components/ui/FilterPills.jsx\` (CONFLICT)
  \`src/components/ui/PortalDrawer.jsx\` (CONFLICT)
  \`src/components/ui/PortalTable.jsx\` (CONFLICT)
  \`src/components/ui/SearchInput.jsx\` (CONFLICT)
  \`src/components/ui/SegmentedControl.jsx\` (CONFLICT)
  \`src/components/ui/SettingCard.jsx\` (CONFLICT)
  \`src/components/ui/Spinner.jsx\` (CONFLICT)
  \`src/components/ui/TabBar.jsx\` (CONFLICT)
  \`src/components/ui/button.jsx\` (CONFLICT)
  \`src/pages/BookingFlow.jsx\` (CONFLICT)
  \`src/pages/DynamicCreditsPage.jsx\` (CONFLICT)
  \`src/pages/DynamicMembershipsPage.jsx\` (CONFLICT)
  \`src/pages/GuestBuyCredits.jsx\` (CONFLICT)
  \`src/pages/Landing.jsx\` (CONFLICT)
  \`src/pages/MembershipSignup.jsx\` (CONFLICT)
  \`src/pages/Register.jsx\` (CONFLICT)
  \`src/pages/RoomProfile.jsx\` (CONFLICT)
  \`src/pages/Services.jsx\` (CONFLICT)
  \`src/pages/Studios.jsx\` (CONFLICT)
  \`src/pages/UnifiedCheckout.jsx\` (CONFLICT)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
  \`src/pages/DynamicCreditsPage.jsx\` (CONFLICT)
  \`src/pages/DynamicMembershipsPage.jsx\` (CONFLICT)
  \`src/pages/GuestBuyCredits.jsx\` (CONFLICT)
  \`src/pages/MembershipSignup.jsx\` (CONFLICT)
  \`src/pages/Register.jsx\` (CONFLICT)
  \`src/pages/UnifiedCheckout.jsx\` (CONFLICT)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
  \`src/pages/Landing.jsx\` (CONFLICT)
  \`src/pages/RoomProfile.jsx\` (CONFLICT)
  \`src/pages/Services.jsx\` (CONFLICT)
  \`src/pages/Studios.jsx\` (CONFLICT)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
  \`src/pages/BookingFlow.jsx\` (CONFLICT)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
  \`src/components/dashboard/MonthCalendar.jsx\` (CONFLICT)
  \`src/components/ipad/FiveMinWarning.jsx\` (CONFLICT)
  \`src/components/ipad/ThankYouScreen.jsx\` (CONFLICT)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
  \`src/components/RoomForm/RoomStudioPreview.jsx\` (CONFLICT)
  \`src/components/RoomForm/WebsitePreviewCard.jsx\` (CONFLICT)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
  \`src/components/MarketingFooter.jsx\` (CONFLICT)
  \`src/components/MarketingHeader.jsx\` (CONFLICT)
  \`src/components/marketing/RoomOperatingHoursDisplay.jsx\` (CONFLICT)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
  \`src/components/booking/BookingDateTimeStep.jsx\` (CONFLICT)
  \`src/components/booking/ClientSelectStep.jsx\` (CONFLICT)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
  \`src/components/ui/EmptyState.jsx\` (CONFLICT)
  \`src/components/ui/FilterPills.jsx\` (CONFLICT)
  \`src/components/ui/PortalDrawer.jsx\` (CONFLICT)
  \`src/components/ui/PortalTable.jsx\` (CONFLICT)
  \`src/components/ui/SearchInput.jsx\` (CONFLICT)
  \`src/components/ui/SegmentedControl.jsx\` (CONFLICT)
  \`src/components/ui/SettingCard.jsx\` (CONFLICT)
  \`src/components/ui/Spinner.jsx\` (CONFLICT)
  \`src/components/ui/TabBar.jsx\` (CONFLICT)
  \`src/components/ui/button.jsx\` (CONFLICT)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
  \`package.json\` (MODIFIED)
  \`project.config.json\` (NEW)
  \`public/_redirects\` (NEW)
  \`scripts/deploy-guard.mjs\` (NEW)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---
## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
- `src/components/ProtectedRoute.jsx` (NEW)
---
## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---
## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---
## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---
## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---
## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---
## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---
## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---
## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---
## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---
## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---
## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---
## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (1× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (NEW)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---
## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---
## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---
## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---
## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---
## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Cod
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Co
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-22 15:33 UTC — dcb2a8e
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files Changed:** 35
**Classification:** 3× NEW | 32× MODIFIED | 0× CONFLICT
- **NEW:** project.config.json, public/_redirects, scripts/deploy-guard.mjs
- **MODIFIED:** package.json, src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx (+27 more)

## 2026-04-22 05:04 UTC — aa4661f
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files Changed:** 6
**Classification:** 0× NEW | 6× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/DynamicCreditsPage.jsx, src/pages/DynamicMembershipsPage.jsx, src/pages/GuestBuyCredits.jsx, src/pages/MembershipSignup.jsx, src/pages/Register.jsx (+1 more)

## 2026-04-22 05:04 UTC — f19cdf0
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/Landing.jsx, src/pages/RoomProfile.jsx, src/pages/Services.jsx, src/pages/Studios.jsx

## 2026-04-22 05:04 UTC — 22cdea7
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/BookingFlow.jsx

## 2026-04-22 05:04 UTC — 3885333
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/dashboard/MonthCalendar.jsx, src/components/ipad/FiveMinWarning.jsx, src/components/ipad/ThankYouScreen.jsx

## 2026-04-22 05:04 UTC — 3564003
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx

## 2026-04-22 05:04 UTC — 923b30e
**Message:** sync: marketing components — refined versions from Claude Code
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/marketing/RoomOperatingHoursDisplay.jsx

## 2026-04-22 05:04 UTC — 18e25d2
**Message:** sync: booking components — refined versions from Claude Code
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/booking/BookingDateTimeStep.jsx, src/components/booking/ClientSelectStep.jsx

## 2026-04-22 05:04 UTC — 762ca5e
**Message:** sync: UI primitives — refined versions from Claude Code
**Files Changed:** 10
**Classification:** 0× NEW | 10× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ui/EmptyState.jsx, src/components/ui/FilterPills.jsx, src/components/ui/PortalDrawer.jsx, src/components/ui/PortalTable.jsx, src/components/ui/SearchInput.jsx (+5 more)

## 2026-04-20 04:07 UTC — 47b2dd6
**Message:** feat: move design site to cloudflare pages
**Files Changed:** 4
**Classification:** 3× NEW | 1× MODIFIED | 0× CONFLICT
- **NEW:** project.config.json, public/_redirects, scripts/deploy-guard.mjs
- **MODIFIED:** package.json

## 2026-04-16 15:28 UTC — 5b06f15
**Message:** Update base44 packages
**Files Changed:** 3
**Classification:** 1× NEW | 2× MODIFIED | 0× CONFLICT
- **NEW:** src/components/ProtectedRoute.jsx
- **MODIFIED:** package-lock.json, package.json

## 2026-04-12 15:14 UTC — 725cf75
**Message:** Update base44 packages
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** package-lock.json, package.json

## 2026-04-12 01:46 UTC — fe64f26
**Message:** File changes
**Files Changed:** 5
**Classification:** 2× NEW | 3× MODIFIED | 0× CONFLICT
- **NEW:** src/database/data-migration-plan.md, src/database/migration-order.json
- **MODIFIED:** src/database/MIGRATION_REPORT.md, src/database/supabase/schema.sql, src/database/types/schema.ts

## 2026-04-12 01:42 UTC — 62d1e6a
**Message:** File changes
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/lib/workflow-data.js, src/pages/AdminWorkflowMap.jsx

## 2026-04-12 01:40 UTC — eb00c62
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx

## 2026-04-12 01:37 UTC — fe80272
**Message:** File changes
**Files Changed:** 7
**Classification:** 7× NEW | 0× MODIFIED | 0× CONFLICT
- **NEW:** src/contracts/schema/enums.json, src/contracts/schema/relationships.json, src/contracts/schema/tables.json, src/database/MIGRATION_REPORT.md, src/database/mappings/base44-map.ts (+2 more)

## 2026-04-12 01:29 UTC — cc98d28
**Message:** File changes
**Files Changed:** 6
**Classification:** 0× NEW | 6× MODIFIED | 0× CONFLICT
- **MODIFIED:** base44/entities/RoomLightingLayout.jsonc, base44/entities/iPadCommand.jsonc, src/components/ipad/InSessionScreen.jsx, src/components/ipad/LightingCanvas.jsx, src/components/ipad/LightingPanel.jsx (+1 more)

## 2026-04-12 01:22 UTC — e2e0de2
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/Landing.jsx

## 2026-04-12 00:52 UTC — 96400df
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/dashboard/PremiumCalendar.jsx

## 2026-04-12 00:49 UTC — e4b13f4
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/lib/workflow-data.js

## 2026-04-12 00:43 UTC — 0a8d94c
**Message:** File changes
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ipad/LightingCanvas.jsx, src/components/ipad/MasterIPadView.jsx

## 2026-04-12 00:39 UTC — 0ddc514
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/dashboard/PremiumCalendar.jsx

## 2026-04-12 00:30 UTC — 01ef5f4
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/AdminWorkflowMap.jsx

## 2026-04-12 00:23 UTC — cc795b7
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ipad/LightingCanvas.jsx, src/components/ipad/MasterIPadView.jsx, src/components/ipad/WelcomeScreen.jsx, src/pages/StudioController.jsx

## 2026-04-12 00:20 UTC — e9c7dad
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/components/dashboard/PremiumCalendar.jsx, src/pages/AdminDashboard.jsx

## 2026-04-12 00:03 UTC — dc5b801
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ipad/WelcomeScreen.jsx, src/pages/AdminiPadController.jsx, src/pages/StudioController.jsx

## 2026-04-11 23:54 UTC — 1aec1f9
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** tailwind.config.js

## 2026-04-11 23:52 UTC — 3f83184
**Message:** File changes
**Files Changed:** 7
**Classification:** 0× NEW | 7× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/components/dashboard/FloatingDayPanel.jsx, src/components/dashboard/SessionTimelineCard.jsx, src/hooks/useTheme.js (+2 more)

## 2026-04-11 23:22 UTC — 0e0a4d2
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/StudioController.jsx

## 2026-04-11 21:26 UTC — 7e2cf42
**Message:** File changes
**Files Changed:** 6
**Classification:** 2× NEW | 4× MODIFIED | 0× CONFLICT
- **NEW:** src/components/ipad/DemoScreen.jsx, src/components/ipad/IdleScreen.jsx
- **MODIFIED:** base44/entities/iPadSession.jsonc, base44/functions/getIPadSession/entry.ts, src/pages/AdminiPadController.jsx, src/pages/StudioController.jsx

## 2026-04-11 21:23 UTC — ca56f4c
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/hooks/useTheme.js

## 2026-04-11 17:53 UTC — 7bd3f84
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ipad/LightingCanvas.jsx, src/components/ipad/LightingPanel.jsx, src/pages/StudioController.jsx

## 2026-04-11 17:33 UTC — 5756d26
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** base44/entities/iPadSession.jsonc, src/components/ipad/InSessionScreen.jsx, src/pages/AdminiPadController.jsx

## 2026-04-11 17:21 UTC — b3b4a95
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/index.css

## 2026-04-11 17:07 UTC — 442a4aa
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/dashboard/PremiumCalendar.jsx, src/components/ui/FloatingPanel.jsx, src/hooks/useTheme.js, src/pages/AdminDashboard.jsx

## 2026-04-11 16:54 UTC — d4df16b
**Message:** File changes
**Files Changed:** 2
**Classification:** 1× NEW | 1× MODIFIED | 0× CONFLICT
- **NEW:** src/components/dashboard/FloatingEventPanel.jsx
- **MODIFIED:** src/components/dashboard/PremiumCalendar.jsx

## 2026-04-11 16:49 UTC — d37f541
**Message:** File changes
**Files Changed:** 5
**Classification:** 0× NEW | 5× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/components/dashboard/PremiumCalendar.jsx, src/components/ui/FloatingPanel.jsx, src/hooks/useTheme.js

## 2026-04-11 16:46 UTC — 981bd65
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/CustomLogin.jsx

## 2026-04-11 16:45 UTC — 3a1682a
**Message:** File changes
**Files Changed:** 6
**Classification:** 2× NEW | 4× MODIFIED | 0× CONFLICT
- **NEW:** base44/entities/iPadCommand.jsonc, base44/functions/iPadVersionControl/entry.ts
- **MODIFIED:** base44/entities/iPadSession.jsonc, index.html, src/pages/AdminiPadController.jsx, src/pages/StudioController.jsx

## 2026-04-11 16:40 UTC — 18612a7
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/dashboard/PremiumCalendar.jsx

## 2026-04-11 16:39 UTC — ad879b0
**Message:** File changes
**Files Changed:** 7
**Classification:** 3× NEW | 4× MODIFIED | 0× CONFLICT
- **NEW:** base44/entities/RoomLightingLayout.jsonc, src/components/ipad/LightingCanvas.jsx, src/components/ipad/MasterIPadView.jsx
- **MODIFIED:** src/components/dashboard/PremiumCalendar.jsx, src/components/ipad/CircularThermostat.jsx, src/components/ipad/InSessionScreen.jsx, src/pages/StudioController.jsx

## 2026-04-11 16:36 UTC — ae210dd
**Message:** File changes
**Files Changed:** 5
**Classification:** 1× NEW | 4× MODIFIED | 0× CONFLICT
- **NEW:** src/components/ui/FloatingPanel.jsx
- **MODIFIED:** src/components/Sidebar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx, src/pages/AdminDashboard.jsx

## 2026-04-11 06:41 UTC — 1c572b9
**Message:** File changes
**Files Changed:** 8
**Classification:** 2× NEW | 6× MODIFIED | 0× CONFLICT
- **NEW:** src/components/ipad/BackgroundLayer.jsx, src/components/ipad/CircularThermostat.jsx
- **MODIFIED:** base44/entities/iPadSession.jsonc, base44/functions/getIPadSession/entry.ts, src/components/ipad/InSessionScreen.jsx, src/components/ipad/WelcomeScreen.jsx, src/pages/AdminiPadController.jsx (+1 more)

## 2026-04-11 06:36 UTC — c2e8650
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/admin/AdminTopbar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx, src/pages/AdminDashboard.jsx

## 2026-04-11 06:28 UTC — 9098ede
**Message:** File changes
**Files Changed:** 2
**Classification:** 0× NEW | 2× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/ipad/InSessionScreen.jsx, src/components/ipad/WelcomeScreen.jsx

## 2026-04-11 06:23 UTC — c323e33
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx

## 2026-04-11 06:22 UTC — a32f6aa
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx

## 2026-04-11 06:14 UTC — 405ff26
**Message:** File changes
**Files Changed:** 4
**Classification:** 0× NEW | 4× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/components/dashboard/PremiumCalendar.jsx, src/hooks/useTheme.js

## 2026-04-11 06:05 UTC — d6bc2b0
**Message:** File changes
**Files Changed:** 1
**Classification:** 0× NEW | 1× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/pages/CustomLogin.jsx

## 2026-04-11 06:00 UTC — e90d8ad
**Message:** File changes
**Files Changed:** 3
**Classification:** 0× NEW | 3× MODIFIED | 0× CONFLICT
- **MODIFIED:** src/components/Sidebar.jsx, src/hooks/useTheme.js, src/pages/AdminDashboard.jsx

# 48Labs Drift Log

Tracking file changes from 48labs-design synced to 48labs-sync.


### dcb2a8e9 — 2026-04-22

**Message:** merge: bring staging sync commits into main (Phase 3 design sync)

**Files Changed:** 35 total
- NEW: 3
- MODIFIED: 32
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### aa4661f4 — 2026-04-22

**Message:** sync: website booking and auth pages — refined versions from Claude Code

**Files Changed:** 6 total
- NEW: 0
- MODIFIED: 6
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### f19cdf03 — 2026-04-22

**Message:** sync: website marketing pages — refined versions from Claude Code

**Files Changed:** 4 total
- NEW: 0
- MODIFIED: 4
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 22cdea70 — 2026-04-22

**Message:** sync: BookingFlow.jsx — refined version from Claude Code

**Files Changed:** 1 total
- NEW: 0
- MODIFIED: 1
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 38853339 — 2026-04-22

**Message:** sync: dashboard and iPad components — refined versions from Claude Code

**Files Changed:** 3 total
- NEW: 0
- MODIFIED: 3
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 3564003b — 2026-04-22

**Message:** sync: RoomForm components — refined versions from Claude Code

**Files Changed:** 2 total
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 923b30e2 — 2026-04-22

**Message:** sync: marketing components — refined versions from Claude Code

**Files Changed:** 3 total
- NEW: 0
- MODIFIED: 3
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 18e25d25 — 2026-04-22

**Message:** sync: booking components — refined versions from Claude Code

**Files Changed:** 2 total
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 762ca5e0 — 2026-04-22

**Message:** sync: UI primitives — refined versions from Claude Code

**Files Changed:** 10 total
- NEW: 0
- MODIFIED: 10
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 47b2dd66 — 2026-04-20

**Message:** feat: move design site to cloudflare pages

**Files Changed:** 4 total
- NEW: 3
- MODIFIED: 1
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 5b06f159 — 2026-04-16

**Message:** Update base44 packages

**Files Changed:** 3 total
- NEW: 1
- MODIFIED: 2
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 725cf756 — 2026-04-12

**Message:** Update base44 packages

**Files Changed:** 2 total
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### fe64f268 — 2026-04-12

**Message:** File changes

**Files Changed:** 5 total
- NEW: 2
- MODIFIED: 3
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### 62d1e6a5 — 2026-04-12

**Message:** File changes

**Files Changed:** 2 total
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Synced from 48labs-design

---


### eb00c62f — 2026-04-12

**Message:** File changes

**Files Changed:** 4 total
- NEW: 0
- MODIFIED: 4
- CONFLICT: 0

**Status:** Synced from 48labs-design

---

## [dcb2a8e] merge: bring staging sync commits into main (Phase 3 design sync)
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 35 (35 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: package.json, project.config.json, public/_redirects, scripts/deploy-guard.mjs, src/components/MarketingFooter.jsx (+30 more)

## [aa4661f] sync: website booking and auth pages — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 6 (6 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/DynamicCreditsPage.jsx, src/pages/DynamicMembershipsPage.jsx, src/pages/GuestBuyCredits.jsx, src/pages/MembershipSignup.jsx, src/pages/Register.jsx (+1 more)

## [f19cdf0] sync: website marketing pages — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/Landing.jsx, src/pages/RoomProfile.jsx, src/pages/Services.jsx, src/pages/Studios.jsx

## [22cdea7] sync: BookingFlow.jsx — refined version from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/BookingFlow.jsx

## [3885333] sync: dashboard and iPad components — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/dashboard/MonthCalendar.jsx, src/components/ipad/FiveMinWarning.jsx, src/components/ipad/ThankYouScreen.jsx

## [3564003] sync: RoomForm components — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/RoomForm/RoomStudioPreview.jsx, src/components/RoomForm/WebsitePreviewCard.jsx

## [923b30e] sync: marketing components — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/MarketingFooter.jsx, src/components/MarketingHeader.jsx, src/components/marketing/RoomOperatingHoursDisplay.jsx

## [18e25d2] sync: booking components — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/booking/BookingDateTimeStep.jsx, src/components/booking/ClientSelectStep.jsx

## [762ca5e] sync: UI primitives — refined versions from Claude Code
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 10 (10 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ui/EmptyState.jsx, src/components/ui/FilterPills.jsx, src/components/ui/PortalDrawer.jsx, src/components/ui/PortalTable.jsx, src/components/ui/SearchInput.jsx (+5 more)

## [47b2dd6] feat: move design site to cloudflare pages
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: package.json, project.config.json, public/_redirects, scripts/deploy-guard.mjs

## [5b06f15] Update base44 packages
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: package-lock.json, package.json, src/components/ProtectedRoute.jsx

## [725cf75] Update base44 packages
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: package-lock.json, package.json

## [fe64f26] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 5 (5 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/database/MIGRATION_REPORT.md, src/database/data-migration-plan.md, src/database/migration-order.json, src/database/supabase/schema.sql, src/database/types/schema.ts

## [62d1e6a] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/lib/workflow-data.js, src/pages/AdminWorkflowMap.jsx

## [eb00c62] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx

## [fe80272] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 7 (7 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/contracts/schema/enums.json, src/contracts/schema/relationships.json, src/contracts/schema/tables.json, src/database/MIGRATION_REPORT.md, src/database/mappings/base44-map.ts (+2 more)

## [cc98d28] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 6 (6 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/RoomLightingLayout.jsonc, base44/entities/iPadCommand.jsonc, src/components/ipad/InSessionScreen.jsx, src/components/ipad/LightingCanvas.jsx, src/components/ipad/LightingPanel.jsx (+1 more)

## [e2e0de2] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/Landing.jsx

## [96400df] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/dashboard/PremiumCalendar.jsx

## [e4b13f4] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/lib/workflow-data.js

## [0a8d94c] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ipad/LightingCanvas.jsx, src/components/ipad/MasterIPadView.jsx

## [0ddc514] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/admin/AdminTopbar.jsx, src/components/dashboard/PremiumCalendar.jsx

## [01ef5f4] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/AdminWorkflowMap.jsx

## [cc795b7] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ipad/LightingCanvas.jsx, src/components/ipad/MasterIPadView.jsx, src/components/ipad/WelcomeScreen.jsx, src/pages/StudioController.jsx

## [e9c7dad] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/components/dashboard/PremiumCalendar.jsx, src/pages/AdminDashboard.jsx

## [dc5b801] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ipad/WelcomeScreen.jsx, src/pages/AdminiPadController.jsx, src/pages/StudioController.jsx

## [1aec1f9] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: tailwind.config.js

## [3f83184] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 7 (7 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/components/dashboard/FloatingDayPanel.jsx, src/components/dashboard/SessionTimelineCard.jsx, src/hooks/useTheme.js (+2 more)

## [0e0a4d2] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/StudioController.jsx

## [7e2cf42] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 6 (6 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/iPadSession.jsonc, base44/functions/getIPadSession/entry.ts, src/components/ipad/DemoScreen.jsx, src/components/ipad/IdleScreen.jsx, src/pages/AdminiPadController.jsx (+1 more)

## [ca56f4c] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/dashboard/DashboardMetricCard.jsx, src/hooks/useTheme.js

## [7bd3f84] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ipad/LightingCanvas.jsx, src/components/ipad/LightingPanel.jsx, src/pages/StudioController.jsx

## [5756d26] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/iPadSession.jsonc, src/components/ipad/InSessionScreen.jsx, src/pages/AdminiPadController.jsx

## [b3b4a95] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/index.css

## [442a4aa] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/dashboard/PremiumCalendar.jsx, src/components/ui/FloatingPanel.jsx, src/hooks/useTheme.js, src/pages/AdminDashboard.jsx

## [d4df16b] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/dashboard/FloatingEventPanel.jsx, src/components/dashboard/PremiumCalendar.jsx

## [d37f541] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 5 (5 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/components/dashboard/PremiumCalendar.jsx, src/components/ui/FloatingPanel.jsx, src/hooks/useTheme.js

## [981bd65] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/CustomLogin.jsx

## [3a1682a] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 6 (6 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/iPadCommand.jsonc, base44/entities/iPadSession.jsonc, base44/functions/iPadVersionControl/entry.ts, index.html, src/pages/AdminiPadController.jsx (+1 more)

## [18612a7] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/dashboard/PremiumCalendar.jsx

## [ad879b0] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 7 (7 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/RoomLightingLayout.jsonc, src/components/dashboard/PremiumCalendar.jsx, src/components/ipad/CircularThermostat.jsx, src/components/ipad/InSessionScreen.jsx, src/components/ipad/LightingCanvas.jsx (+2 more)

## [ae210dd] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 5 (5 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx, src/components/ui/FloatingPanel.jsx, src/pages/AdminDashboard.jsx

## [1c572b9] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 8 (8 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: base44/entities/iPadSession.jsonc, base44/functions/getIPadSession/entry.ts, src/components/ipad/BackgroundLayer.jsx, src/components/ipad/CircularThermostat.jsx, src/components/ipad/InSessionScreen.jsx (+3 more)

## [c2e8650] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/admin/AdminTopbar.jsx, src/components/admin/QuickActionsDropdown.jsx, src/components/dashboard/PremiumCalendar.jsx, src/pages/AdminDashboard.jsx

## [9098ede] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 2 (2 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/ipad/InSessionScreen.jsx, src/components/ipad/WelcomeScreen.jsx

## [c323e33] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx

## [a32f6aa] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx

## [405ff26] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 4 (4 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/AdminLayout.jsx, src/components/Sidebar.jsx, src/components/dashboard/PremiumCalendar.jsx, src/hooks/useTheme.js

## [d6bc2b0] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 1 (1 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/pages/CustomLogin.jsx

## [e90d8ad] File changes
**Date:** 2026-04-24 12:21 UTC  
**Files changed:** 3 (3 NEW, 0 MODIFIED, 0 CONFLICT)  
**Details:**
- NEW: src/components/Sidebar.jsx, src/hooks/useTheme.js, src/pages/AdminDashboard.jsx
## 2026-04-22 | dcb2a8e | NEW: 3, MODIFIED: 32, CONFLICT: 0

**Message:** merge: bring staging sync commits into main (Phase 3 design sync)

**NEW files:**
- project.config.json
- public/_redirects
- scripts/deploy-guard.mjs

**MODIFIED files:**
- package.json
- src/components/MarketingFooter.jsx
- src/components/MarketingHeader.jsx
- src/components/RoomForm/RoomStudioPreview.jsx
- src/components/RoomForm/WebsitePreviewCard.jsx
- src/components/booking/BookingDateTimeStep.jsx
- src/components/booking/ClientSelectStep.jsx
- src/components/dashboard/MonthCalendar.jsx
- src/components/ipad/FiveMinWarning.jsx
- src/components/ipad/ThankYouScreen.jsx
- src/components/marketing/RoomOperatingHoursDisplay.jsx
- src/components/ui/EmptyState.jsx
- src/components/ui/FilterPills.jsx
- src/components/ui/PortalDrawer.jsx
- src/components/ui/PortalTable.jsx
- src/components/ui/SearchInput.jsx
- src/components/ui/SegmentedControl.jsx
- src/components/ui/SettingCard.jsx
- src/components/ui/Spinner.jsx
- src/components/ui/TabBar.jsx
- src/components/ui/button.jsx
- src/pages/BookingFlow.jsx
- src/pages/DynamicCreditsPage.jsx
- src/pages/DynamicMembershipsPage.jsx
- src/pages/GuestBuyCredits.jsx
- src/pages/Landing.jsx
- src/pages/MembershipSignup.jsx
- src/pages/Register.jsx
- src/pages/RoomProfile.jsx
- src/pages/Services.jsx
- src/pages/Studios.jsx
- src/pages/UnifiedCheckout.jsx

---

## 2026-04-22 | aa4661f | NEW: 0, MODIFIED: 6, CONFLICT: 0

**Message:** sync: website booking and auth pages — refined versions from Claude Code

**MODIFIED files:**
- src/pages/DynamicCreditsPage.jsx
- src/pages/DynamicMembershipsPage.jsx
- src/pages/GuestBuyCredits.jsx
- src/pages/MembershipSignup.jsx
- src/pages/Register.jsx
- src/pages/UnifiedCheckout.jsx

---

## 2026-04-22 | f19cdf0 | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** sync: website marketing pages — refined versions from Claude Code

**MODIFIED files:**
- src/pages/Landing.jsx
- src/pages/RoomProfile.jsx
- src/pages/Services.jsx
- src/pages/Studios.jsx

---

## 2026-04-22 | 22cdea7 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** sync: BookingFlow.jsx — refined version from Claude Code

**MODIFIED files:**
- src/pages/BookingFlow.jsx

---

## 2026-04-22 | 3885333 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** sync: dashboard and iPad components — refined versions from Claude Code

**MODIFIED files:**
- src/components/dashboard/MonthCalendar.jsx
- src/components/ipad/FiveMinWarning.jsx
- src/components/ipad/ThankYouScreen.jsx

---

## 2026-04-22 | 3564003 | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** sync: RoomForm components — refined versions from Claude Code

**MODIFIED files:**
- src/components/RoomForm/RoomStudioPreview.jsx
- src/components/RoomForm/WebsitePreviewCard.jsx

---

## 2026-04-22 | 923b30e | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** sync: marketing components — refined versions from Claude Code

**MODIFIED files:**
- src/components/MarketingFooter.jsx
- src/components/MarketingHeader.jsx
- src/components/marketing/RoomOperatingHoursDisplay.jsx

---

## 2026-04-22 | 18e25d2 | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** sync: booking components — refined versions from Claude Code

**MODIFIED files:**
- src/components/booking/BookingDateTimeStep.jsx
- src/components/booking/ClientSelectStep.jsx

---

## 2026-04-22 | 762ca5e | NEW: 0, MODIFIED: 10, CONFLICT: 0

**Message:** sync: UI primitives — refined versions from Claude Code

**MODIFIED files:**
- src/components/ui/EmptyState.jsx
- src/components/ui/FilterPills.jsx
- src/components/ui/PortalDrawer.jsx
- src/components/ui/PortalTable.jsx
- src/components/ui/SearchInput.jsx
- src/components/ui/SegmentedControl.jsx
- src/components/ui/SettingCard.jsx
- src/components/ui/Spinner.jsx
- src/components/ui/TabBar.jsx
- src/components/ui/button.jsx

---

## 2026-04-20 | 47b2dd6 | NEW: 3, MODIFIED: 1, CONFLICT: 0

**Message:** feat: move design site to cloudflare pages

**NEW files:**
- project.config.json
- public/_redirects
- scripts/deploy-guard.mjs

**MODIFIED files:**
- package.json

---

## 2026-04-16 | 5b06f15 | NEW: 1, MODIFIED: 2, CONFLICT: 0

**Message:** Update base44 packages

**NEW files:**
- src/components/ProtectedRoute.jsx

**MODIFIED files:**
- package-lock.json
- package.json

---

## 2026-04-12 | 725cf75 | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** Update base44 packages

**MODIFIED files:**
- package-lock.json
- package.json

---

## 2026-04-12 | fe64f26 | NEW: 2, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/database/data-migration-plan.md
- src/database/migration-order.json

**MODIFIED files:**
- src/database/MIGRATION_REPORT.md
- src/database/supabase/schema.sql
- src/database/types/schema.ts

---

## 2026-04-12 | 62d1e6a | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/lib/workflow-data.js
- src/pages/AdminWorkflowMap.jsx

---

## 2026-04-12 | eb00c62 | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/admin/AdminTopbar.jsx
- src/components/admin/QuickActionsDropdown.jsx
- src/components/dashboard/PremiumCalendar.jsx

---

## 2026-04-12 | fe80272 | NEW: 7, MODIFIED: 0, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/contracts/schema/enums.json
- src/contracts/schema/relationships.json
- src/contracts/schema/tables.json
- src/database/MIGRATION_REPORT.md
- src/database/mappings/base44-map.ts
- src/database/supabase/schema.sql
- src/database/types/schema.ts

---

## 2026-04-12 | cc98d28 | NEW: 0, MODIFIED: 6, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- base44/entities/RoomLightingLayout.jsonc
- base44/entities/iPadCommand.jsonc
- src/components/ipad/InSessionScreen.jsx
- src/components/ipad/LightingCanvas.jsx
- src/components/ipad/LightingPanel.jsx
- src/components/ipad/MasterIPadView.jsx

---

## 2026-04-12 | e2e0de2 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/pages/Landing.jsx

---

## 2026-04-12 | 96400df | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/admin/AdminTopbar.jsx
- src/components/dashboard/PremiumCalendar.jsx

---

## 2026-04-12 | e4b13f4 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/lib/workflow-data.js

---

## 2026-04-12 | 0a8d94c | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/ipad/LightingCanvas.jsx
- src/components/ipad/MasterIPadView.jsx

---

## 2026-04-12 | 0ddc514 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/admin/AdminTopbar.jsx
- src/components/dashboard/PremiumCalendar.jsx

---

## 2026-04-12 | 01ef5f4 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/pages/AdminWorkflowMap.jsx

---

## 2026-04-12 | cc795b7 | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/ipad/LightingCanvas.jsx
- src/components/ipad/MasterIPadView.jsx
- src/components/ipad/WelcomeScreen.jsx
- src/pages/StudioController.jsx

---

## 2026-04-12 | e9c7dad | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/admin/QuickActionsDropdown.jsx
- src/components/dashboard/DashboardMetricCard.jsx
- src/components/dashboard/PremiumCalendar.jsx
- src/pages/AdminDashboard.jsx

---

## 2026-04-12 | dc5b801 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/ipad/WelcomeScreen.jsx
- src/pages/AdminiPadController.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | 1aec1f9 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- tailwind.config.js

---

## 2026-04-11 | 3f83184 | NEW: 0, MODIFIED: 7, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/dashboard/DashboardMetricCard.jsx
- src/components/dashboard/FloatingDayPanel.jsx
- src/components/dashboard/SessionTimelineCard.jsx
- src/hooks/useTheme.js
- src/index.css
- tailwind.config.js

---

## 2026-04-11 | 0e0a4d2 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/pages/StudioController.jsx

---

## 2026-04-11 | 7e2cf42 | NEW: 2, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/components/ipad/DemoScreen.jsx
- src/components/ipad/IdleScreen.jsx

**MODIFIED files:**
- base44/entities/iPadSession.jsonc
- base44/functions/getIPadSession/entry.ts
- src/pages/AdminiPadController.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | ca56f4c | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/dashboard/DashboardMetricCard.jsx
- src/hooks/useTheme.js

---

## 2026-04-11 | 7bd3f84 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/ipad/LightingCanvas.jsx
- src/components/ipad/LightingPanel.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | 5756d26 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- base44/entities/iPadSession.jsonc
- src/components/ipad/InSessionScreen.jsx
- src/pages/AdminiPadController.jsx

---

## 2026-04-11 | b3b4a95 | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/AdminLayout.jsx
- src/components/Sidebar.jsx
- src/index.css

---

## 2026-04-11 | 442a4aa | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/dashboard/PremiumCalendar.jsx
- src/components/ui/FloatingPanel.jsx
- src/hooks/useTheme.js
- src/pages/AdminDashboard.jsx

---

## 2026-04-11 | d4df16b | NEW: 1, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/components/dashboard/FloatingEventPanel.jsx

**MODIFIED files:**
- src/components/dashboard/PremiumCalendar.jsx

---

## 2026-04-11 | d37f541 | NEW: 0, MODIFIED: 5, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/AdminLayout.jsx
- src/components/Sidebar.jsx
- src/components/dashboard/PremiumCalendar.jsx
- src/components/ui/FloatingPanel.jsx
- src/hooks/useTheme.js

---

## 2026-04-11 | 981bd65 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/pages/CustomLogin.jsx

---

## 2026-04-11 | 3a1682a | NEW: 2, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**NEW files:**
- base44/entities/iPadCommand.jsonc
- base44/functions/iPadVersionControl/entry.ts

**MODIFIED files:**
- base44/entities/iPadSession.jsonc
- index.html
- src/pages/AdminiPadController.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | 18612a7 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/dashboard/PremiumCalendar.jsx

---

## 2026-04-11 | ad879b0 | NEW: 3, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**NEW files:**
- base44/entities/RoomLightingLayout.jsonc
- src/components/ipad/LightingCanvas.jsx
- src/components/ipad/MasterIPadView.jsx

**MODIFIED files:**
- src/components/dashboard/PremiumCalendar.jsx
- src/components/ipad/CircularThermostat.jsx
- src/components/ipad/InSessionScreen.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | ae210dd | NEW: 1, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/components/ui/FloatingPanel.jsx

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/components/admin/QuickActionsDropdown.jsx
- src/components/dashboard/PremiumCalendar.jsx
- src/pages/AdminDashboard.jsx

---

## 2026-04-11 | 1c572b9 | NEW: 2, MODIFIED: 6, CONFLICT: 0

**Message:** File changes

**NEW files:**
- src/components/ipad/BackgroundLayer.jsx
- src/components/ipad/CircularThermostat.jsx

**MODIFIED files:**
- base44/entities/iPadSession.jsonc
- base44/functions/getIPadSession/entry.ts
- src/components/ipad/InSessionScreen.jsx
- src/components/ipad/WelcomeScreen.jsx
- src/pages/AdminiPadController.jsx
- src/pages/StudioController.jsx

---

## 2026-04-11 | c2e8650 | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/admin/AdminTopbar.jsx
- src/components/admin/QuickActionsDropdown.jsx
- src/components/dashboard/PremiumCalendar.jsx
- src/pages/AdminDashboard.jsx

---

## 2026-04-11 | 9098ede | NEW: 0, MODIFIED: 2, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/ipad/InSessionScreen.jsx
- src/components/ipad/WelcomeScreen.jsx

---

## 2026-04-11 | c323e33 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx

---

## 2026-04-11 | a32f6aa | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx

---

## 2026-04-11 | 405ff26 | NEW: 0, MODIFIED: 4, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/AdminLayout.jsx
- src/components/Sidebar.jsx
- src/components/dashboard/PremiumCalendar.jsx
- src/hooks/useTheme.js

---

## 2026-04-11 | d6bc2b0 | NEW: 0, MODIFIED: 1, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/pages/CustomLogin.jsx

---

## 2026-04-11 | e90d8ad | NEW: 0, MODIFIED: 3, CONFLICT: 0

**Message:** File changes

**MODIFIED files:**
- src/components/Sidebar.jsx
- src/hooks/useTheme.js
- src/pages/AdminDashboard.jsx

---


## dcb2a8e — 2026-04-22T15:33:13

**Message:** merge: bring staging sync commits into main (Phase 3 design sync)

**Files Changed:** 35
- NEW: 3
- MODIFIED: 32
- CONFLICT: 0

**Status:** Logged


## aa4661f — 2026-04-22T05:04:47

**Message:** sync: website booking and auth pages — refined versions from Claude Code

**Files Changed:** 6
- NEW: 0
- MODIFIED: 6
- CONFLICT: 0

**Status:** Logged


## f19cdf0 — 2026-04-22T05:04:42

**Message:** sync: website marketing pages — refined versions from Claude Code

**Files Changed:** 4
- NEW: 0
- MODIFIED: 4
- CONFLICT: 0

**Status:** Logged


## 22cdea7 — 2026-04-22T05:04:36

**Message:** sync: BookingFlow.jsx — refined version from Claude Code

**Files Changed:** 1
- NEW: 0
- MODIFIED: 1
- CONFLICT: 0

**Status:** Logged


## 3885333 — 2026-04-22T05:04:31

**Message:** sync: dashboard and iPad components — refined versions from Claude Code

**Files Changed:** 3
- NEW: 0
- MODIFIED: 3
- CONFLICT: 0

**Status:** Logged


## 3564003 — 2026-04-22T05:04:23

**Message:** sync: RoomForm components — refined versions from Claude Code

**Files Changed:** 2
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Logged


## 923b30e — 2026-04-22T05:04:19

**Message:** sync: marketing components — refined versions from Claude Code

**Files Changed:** 3
- NEW: 0
- MODIFIED: 3
- CONFLICT: 0

**Status:** Logged


## 18e25d2 — 2026-04-22T05:04:15

**Message:** sync: booking components — refined versions from Claude Code

**Files Changed:** 2
- NEW: 0
- MODIFIED: 2
- CONFLICT: 0

**Status:** Logged


## 762ca5e — 2026-04-22T05:04:10

**Message:** sync: UI primitives — refined versions from Claude Code

**Files Changed:** 10
- NEW: 0
- MODIFIED: 10
- CONFLICT: 0

**Status:** Logged


## 47b2dd6 — 2026-04-20T04:07:52

**Message:** feat: move design site to cloudflare pages

**Files Changed:** 4
- NEW: 3
- MODIFIED: 1
- CONFLICT: 0

**Status:** Logged

## dcb2a8e9 — 2026-04-22 15:33 UTC

**Message:** merge: bring staging sync commits into main (Phase 3 design sync)

**Files:** 35 changed (3× NEW | 32× MODIFIED)


## aa4661f4 — 2026-04-22 05:04 UTC

**Message:** sync: website booking and auth pages — refined versions from Claude Code

**Files:** 6 changed (6× MODIFIED)


## f19cdf03 — 2026-04-22 05:04 UTC

**Message:** sync: website marketing pages — refined versions from Claude Code

**Files:** 4 changed (4× MODIFIED)


## 22cdea70 — 2026-04-22 05:04 UTC

**Message:** sync: BookingFlow.jsx — refined version from Claude Code

**Files:** 1 changed (1× MODIFIED)


## 38853339 — 2026-04-22 05:04 UTC

**Message:** sync: dashboard and iPad components — refined versions from Claude Code

**Files:** 3 changed (3× MODIFIED)


## 3564003b — 2026-04-22 05:04 UTC

**Message:** sync: RoomForm components — refined versions from Claude Code

**Files:** 2 changed (2× MODIFIED)


## 923b30e2 — 2026-04-22 05:04 UTC

**Message:** sync: marketing components — refined versions from Claude Code

**Files:** 3 changed (3× MODIFIED)


## 18e25d25 — 2026-04-22 05:04 UTC

**Message:** sync: booking components — refined versions from Claude Code

**Files:** 2 changed (2× MODIFIED)


## 762ca5e0 — 2026-04-22 05:04 UTC

**Message:** sync: UI primitives — refined versions from Claude Code

**Files:** 10 changed (10× MODIFIED)


## 47b2dd66 — 2026-04-20 04:07 UTC

**Message:** feat: move design site to cloudflare pages

**Files:** 4 changed (3× NEW | 1× MODIFIED)


## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
**Classification:**
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---

## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
- `src/components/ProtectedRoute.jsx` (NEW)
---

## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---

## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---

## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/Landing.jsx` (MODIFIED)
---

## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/lib/workflow-data.js` (MODIFIED)
---

## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---

## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---

## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 5× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (1× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (NEW)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
**Classification:**
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---

## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
**Classification:**
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-20 47B2DD66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---

## 2026-04-22 762CA5E0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-22 18E25D25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 923B30E2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 3564003B
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 22CDEA70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 F19CDF03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 AA4661F4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 DCB2A8E9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---


## 2026-04-24 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-24 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-24 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-24 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-24 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-24 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-24 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-24 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-24 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ProtectedRoute.jsx` (NEW)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---

## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---

## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
---

## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---

## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---

## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---

## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 5× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (1× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ui/FloatingPanel.jsx` (NEW)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---

## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 32× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
- `src/pages/BookingFlow.jsx` (MODIFIED)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---
## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (MODIFIED)
- `src/pages/DynamicMembershipsPage.jsx` (MODIFIED)
- `src/pages/GuestBuyCredits.jsx` (MODIFIED)
- `src/pages/MembershipSignup.jsx` (MODIFIED)
- `src/pages/Register.jsx` (MODIFIED)
- `src/pages/UnifiedCheckout.jsx` (MODIFIED)
---
## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/pages/Landing.jsx` (MODIFIED)
- `src/pages/RoomProfile.jsx` (MODIFIED)
- `src/pages/Services.jsx` (MODIFIED)
- `src/pages/Studios.jsx` (MODIFIED)
---
## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/BookingFlow.jsx` (MODIFIED)
---
## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (MODIFIED)
- `src/components/ipad/FiveMinWarning.jsx` (MODIFIED)
- `src/components/ipad/ThankYouScreen.jsx` (MODIFIED)
---
## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (MODIFIED)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (MODIFIED)
---
## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/MarketingFooter.jsx` (MODIFIED)
- `src/components/MarketingHeader.jsx` (MODIFIED)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (MODIFIED)
---
## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (MODIFIED)
- `src/components/booking/ClientSelectStep.jsx` (MODIFIED)
---
## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 10× MODIFIED | 0× CONFLICT)
- `src/components/ui/EmptyState.jsx` (MODIFIED)
- `src/components/ui/FilterPills.jsx` (MODIFIED)
- `src/components/ui/PortalDrawer.jsx` (MODIFIED)
- `src/components/ui/PortalTable.jsx` (MODIFIED)
- `src/components/ui/SearchInput.jsx` (MODIFIED)
- `src/components/ui/SegmentedControl.jsx` (MODIFIED)
- `src/components/ui/SettingCard.jsx` (MODIFIED)
- `src/components/ui/Spinner.jsx` (MODIFIED)
- `src/components/ui/TabBar.jsx` (MODIFIED)
- `src/components/ui/button.jsx` (MODIFIED)
---
## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-16 5b06f159
**Message:** Update base44 packages
**Files changed:** 3 (1× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ProtectedRoute.jsx` (NEW)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 725cf756
**Message:** Update base44 packages
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `package-lock.json` (MODIFIED)
- `package.json` (MODIFIED)
---

## 2026-04-12 fe64f268
**Message:** File changes
**Files changed:** 5 (2× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/database/data-migration-plan.md` (NEW)
- `src/database/migration-order.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (MODIFIED)
- `src/database/supabase/schema.sql` (MODIFIED)
- `src/database/types/schema.ts` (MODIFIED)
---

## 2026-04-12 62d1e6a5
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 eb00c62f
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 fe80272b
**Message:** File changes
**Files changed:** 7 (7× NEW | 0× MODIFIED | 0× CONFLICT)
- `src/contracts/schema/enums.json` (NEW)
- `src/contracts/schema/relationships.json` (NEW)
- `src/contracts/schema/tables.json` (NEW)
- `src/database/MIGRATION_REPORT.md` (NEW)
- `src/database/mappings/base44-map.ts` (NEW)
- `src/database/supabase/schema.sql` (NEW)
- `src/database/types/schema.ts` (NEW)
---

## 2026-04-12 cc98d284
**Message:** File changes
**Files changed:** 6 (0× NEW | 6× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (MODIFIED)
- `base44/entities/iPadCommand.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 e2e0de2e
**Message:** File changes
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
---

## 2026-04-12 96400df4
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 e4b13f4b
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/lib/workflow-data.js` (MODIFIED)
---

## 2026-04-12 0a8d94c4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
---

## 2026-04-12 0ddc5140
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-12 01ef5f43
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/AdminWorkflowMap.jsx` (MODIFIED)
---

## 2026-04-12 cc795b75
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/MasterIPadView.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-12 e9c7dad7
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-12 dc5b801f
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 1aec1f99
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 3f83184f
**Message:** File changes
**Files changed:** 7 (0× NEW | 7× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/components/dashboard/FloatingDayPanel.jsx` (MODIFIED)
- `src/components/dashboard/SessionTimelineCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/index.css` (MODIFIED)
- `tailwind.config.js` (MODIFIED)
---

## 2026-04-11 0e0a4d29
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 7e2cf42d
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/ipad/DemoScreen.jsx` (NEW)
- `src/components/ipad/IdleScreen.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ca56f4c8
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/DashboardMetricCard.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 7bd3f848
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/ipad/LightingCanvas.jsx` (MODIFIED)
- `src/components/ipad/LightingPanel.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 5756d26d
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
---

## 2026-04-11 b3b4a959
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/index.css` (MODIFIED)
---

## 2026-04-11 442a4aa6
**Message:** File changes
**Files changed:** 4 (0× NEW | 3× MODIFIED | 1× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 d4df16bd
**Message:** File changes
**Files changed:** 2 (1× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/FloatingEventPanel.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 d37f5413
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 981bd655
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 3a1682a1
**Message:** File changes
**Files changed:** 6 (2× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/iPadCommand.jsonc` (NEW)
- `base44/functions/iPadVersionControl/entry.ts` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `index.html` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 18612a7d
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
---

## 2026-04-11 ad879b0b
**Message:** File changes
**Files changed:** 7 (3× NEW | 4× MODIFIED | 0× CONFLICT)
- `base44/entities/RoomLightingLayout.jsonc` (NEW)
- `src/components/ipad/LightingCanvas.jsx` (NEW)
- `src/components/ipad/MasterIPadView.jsx` (NEW)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/components/ipad/CircularThermostat.jsx` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 ae210dd2
**Message:** File changes
**Files changed:** 5 (0× NEW | 4× MODIFIED | 1× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
- `src/components/ui/FloatingPanel.jsx` (CONFLICT)
---

## 2026-04-11 1c572b9d
**Message:** File changes
**Files changed:** 8 (2× NEW | 6× MODIFIED | 0× CONFLICT)
- `src/components/ipad/BackgroundLayer.jsx` (NEW)
- `src/components/ipad/CircularThermostat.jsx` (NEW)
- `base44/entities/iPadSession.jsonc` (MODIFIED)
- `base44/functions/getIPadSession/entry.ts` (MODIFIED)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
- `src/pages/AdminiPadController.jsx` (MODIFIED)
- `src/pages/StudioController.jsx` (MODIFIED)
---

## 2026-04-11 c2e86504
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/admin/AdminTopbar.jsx` (MODIFIED)
- `src/components/admin/QuickActionsDropdown.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---

## 2026-04-11 9098ede4
**Message:** File changes
**Files changed:** 2 (0× NEW | 2× MODIFIED | 0× CONFLICT)
- `src/components/ipad/InSessionScreen.jsx` (MODIFIED)
- `src/components/ipad/WelcomeScreen.jsx` (MODIFIED)
---

## 2026-04-11 c323e33f
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 a32f6aaf
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
---

## 2026-04-11 405ff264
**Message:** File changes
**Files changed:** 4 (0× NEW | 4× MODIFIED | 0× CONFLICT)
- `src/components/AdminLayout.jsx` (MODIFIED)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/components/dashboard/PremiumCalendar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
---

## 2026-04-11 d6bc2b03
**Message:** File changes
**Files changed:** 1 (0× NEW | 1× MODIFIED | 0× CONFLICT)
- `src/pages/CustomLogin.jsx` (MODIFIED)
---

## 2026-04-11 e90d8ade
**Message:** File changes
**Files changed:** 3 (0× NEW | 3× MODIFIED | 0× CONFLICT)
- `src/components/Sidebar.jsx` (MODIFIED)
- `src/hooks/useTheme.js` (MODIFIED)
- `src/pages/AdminDashboard.jsx` (MODIFIED)
---
## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---

## 2026-04-22 dcb2a8e9
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- ... and 25 more
---

## 2026-04-22 aa4661f4
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf03
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea70
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 38853339
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003b
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e2
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d25
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e0
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd66
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `package.json` (MODIFIED)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
---## 2026-04-22 dcb2a8e
**Message:** merge: bring staging sync commits into main (Phase 3 design sync)
**Files changed:** 35 (3× NEW | 1× MODIFIED | 31× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 aa4661f
**Message:** sync: website booking and auth pages — refined versions from Claude Code
**Files changed:** 6 (0× NEW | 0× MODIFIED | 6× CONFLICT)
- `src/pages/DynamicCreditsPage.jsx` (CONFLICT)
- `src/pages/DynamicMembershipsPage.jsx` (CONFLICT)
- `src/pages/GuestBuyCredits.jsx` (CONFLICT)
- `src/pages/MembershipSignup.jsx` (CONFLICT)
- `src/pages/Register.jsx` (CONFLICT)
- `src/pages/UnifiedCheckout.jsx` (CONFLICT)
---

## 2026-04-22 f19cdf0
**Message:** sync: website marketing pages — refined versions from Claude Code
**Files changed:** 4 (0× NEW | 0× MODIFIED | 4× CONFLICT)
- `src/pages/Landing.jsx` (CONFLICT)
- `src/pages/RoomProfile.jsx` (CONFLICT)
- `src/pages/Services.jsx` (CONFLICT)
- `src/pages/Studios.jsx` (CONFLICT)
---

## 2026-04-22 22cdea7
**Message:** sync: BookingFlow.jsx — refined version from Claude Code
**Files changed:** 1 (0× NEW | 0× MODIFIED | 1× CONFLICT)
- `src/pages/BookingFlow.jsx` (CONFLICT)
---

## 2026-04-22 3885333
**Message:** sync: dashboard and iPad components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/dashboard/MonthCalendar.jsx` (CONFLICT)
- `src/components/ipad/FiveMinWarning.jsx` (CONFLICT)
- `src/components/ipad/ThankYouScreen.jsx` (CONFLICT)
---

## 2026-04-22 3564003
**Message:** sync: RoomForm components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/RoomForm/RoomStudioPreview.jsx` (CONFLICT)
- `src/components/RoomForm/WebsitePreviewCard.jsx` (CONFLICT)
---

## 2026-04-22 923b30e
**Message:** sync: marketing components — refined versions from Claude Code
**Files changed:** 3 (0× NEW | 0× MODIFIED | 3× CONFLICT)
- `src/components/MarketingFooter.jsx` (CONFLICT)
- `src/components/MarketingHeader.jsx` (CONFLICT)
- `src/components/marketing/RoomOperatingHoursDisplay.jsx` (CONFLICT)
---

## 2026-04-22 18e25d2
**Message:** sync: booking components — refined versions from Claude Code
**Files changed:** 2 (0× NEW | 0× MODIFIED | 2× CONFLICT)
- `src/components/booking/BookingDateTimeStep.jsx` (CONFLICT)
- `src/components/booking/ClientSelectStep.jsx` (CONFLICT)
---

## 2026-04-22 762ca5e
**Message:** sync: UI primitives — refined versions from Claude Code
**Files changed:** 10 (0× NEW | 0× MODIFIED | 10× CONFLICT)
- `src/components/ui/EmptyState.jsx` (CONFLICT)
- `src/components/ui/FilterPills.jsx` (CONFLICT)
- `src/components/ui/PortalDrawer.jsx` (CONFLICT)
- `src/components/ui/PortalTable.jsx` (CONFLICT)
- `src/components/ui/SearchInput.jsx` (CONFLICT)
- `src/components/ui/SegmentedControl.jsx` (CONFLICT)
- `src/components/ui/SettingCard.jsx` (CONFLICT)
- `src/components/ui/Spinner.jsx` (CONFLICT)
- `src/components/ui/TabBar.jsx` (CONFLICT)
- `src/components/ui/button.jsx` (CONFLICT)
---

## 2026-04-20 47b2dd6
**Message:** feat: move design site to cloudflare pages
**Files changed:** 4 (3× NEW | 1× MODIFIED | 0× CONFLICT)
- `project.config.json` (NEW)
- `public/_redirects` (NEW)
- `scripts/deploy-guard.mjs` (NEW)
- `package.json` (MODIFIED)
---
