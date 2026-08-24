# Ezekiel Job Search Dashboard

Current queues:
- DFW: 25 active
- Greater Houston: 10
- New York: 10
- Chicago: 10
- Remote / Nationwide: 10 Texas-eligible roles
- Plus Watchlist items

## Why `jobs.json` is separate
`index.html` now fetches `jobs.json` every time the site loads. That means the daily updater can replace only `jobs.json` and the website immediately reflects the refreshed job list without rebuilding the interface.

## GitHub Pages setup
1. Create a public GitHub repository named `job-search-dashboard`.
2. Upload `index.html`, `jobs.json`, and `README.md` to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch.
5. Select `main` and `/(root)`.
6. Save and bookmark the GitHub Pages URL.

Application statuses, notes, and action timestamps are stored in browser localStorage. Use the dashboard's CSV export for backup before changing browsers/devices.
