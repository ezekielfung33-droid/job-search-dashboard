# Ezekiel Job Search Dashboard

Current source queues (Aug 30, 2026 refresh):
- DFW: 30 active
- Greater Houston: 11
- New York: 11
- Chicago: 11
- Remote / Nationwide: 11 Texas-eligible roles
- Plus 1 Watchlist item
- Plus 2 Closed items retained for history

This refresh added six verified opportunities, moved expired/no-longer-verifiable postings out of the active queue, corrected direct links, and recalibrated several fit scores against current requirements. Existing job IDs and browser-storage keys were preserved so saved statuses and notes continue to map to the same jobs.

## New Aug. 30 opportunities
- Optum / UnitedHealth Group — Strategy Analyst, Life Sciences — National Remote
- Third Bridge — Associate, Client Services — 2027 Start Dates — Dallas
- Texas Oncology — Data Coordinator — Dallas Sammons — Hybrid
- Robert Half — Business Analyst I — Houston
- Fitch Ratings — Business Analyst — Chicago
- Fitch Ratings — Business Analyst — New York

## Why `jobs.json` is separate
`index.html` fetches `jobs.json` every time the site loads. Application statuses, notes, and action timestamps remain browser-local.

## Publishing this refresh
Replace `index.html`, `jobs.json`, and `README.md` in the repository root and commit. GitHub Pages will redeploy automatically. This refresh updates the visible audit date/market badges in `index.html`, so replace all three files this time.

Use the dashboard's CSV export before switching browsers/devices.
