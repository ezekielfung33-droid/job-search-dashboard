# Ezekiel Job Search Dashboard

Current queues (Aug 26, 2026 refresh):
- DFW: 29 active
- Greater Houston: 10
- New York: 10
- Chicago: 10
- Remote / Nationwide: 11 Texas-eligible roles
- Plus 1 Watchlist item

Today’s refresh added five verified opportunities and refreshed the UnitedHealthcare OON dispute role against a current posting. Existing application IDs were preserved so browser-saved statuses and notes continue to map to the same jobs.

## Why `jobs.json` is separate
`index.html` fetches `jobs.json` every time the site loads. That means a refresh can replace only `jobs.json` and the website immediately reflects the updated job list without rebuilding the interface.

## GitHub Pages setup
1. Keep `index.html`, `jobs.json`, and `README.md` in the repository root.
2. GitHub Pages should deploy from `main` and `/(root)`.
3. To publish a refresh, replace the three files and commit the changes. Pages redeploys automatically.

Application statuses, notes, and action timestamps are stored in browser localStorage. Use the dashboard's CSV export for backup before changing browsers/devices.
