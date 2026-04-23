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
