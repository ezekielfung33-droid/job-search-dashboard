# Ezekiel Job Search Dashboard — Aug. 31, 2026 Refresh

This refresh widens the funnel beyond healthcare toward:
- Business Analyst
- Operations / Process Analyst
- Finance / FP&A
- Risk / Controls
- Strategy / Planning
- Project / entry-level corporate roles
- Healthcare analyst roles when they are a strong fit

## Files in this update
- `index.html` — updated dashboard interface; merges the existing board with the Aug. 31 additions.
- `jobs_aug31.json` — Aug. 31 additions / refreshed records.
- `README.md` — these instructions.

## Important: keep your existing `jobs.json`
Do **not** delete the existing `jobs.json` from the repository. The updated `index.html` loads:
1. the existing `jobs.json`, then
2. `jobs_aug31.json`

Records are merged by stable job `id`, so:
- older jobs stay on the board,
- refreshed jobs can overwrite older metadata without creating duplicates,
- browser-saved application statuses and notes continue to map to the same IDs.

## GitHub Pages deployment
Your repository root should contain:
- `index.html`
- `jobs.json` (existing file — keep it)
- `jobs_aug31.json` (new)
- `README.md`

Upload/replace `index.html` and `README.md`, add `jobs_aug31.json`, leave `jobs.json` in place, and commit to `main`. GitHub Pages will redeploy from the repository root.

## Aug. 31 priority additions
Highest-priority new targets include:
1. Bank of America — Risk Process Analyst
2. American Airlines — Analyst/Sr Analyst, Financial Planning & Analysis
3. Gartner — Business Analyst, Conferences Sales Operations
4. CHRISTUS Health — Financial Analyst I
5. Bank of America — Commercial Credit Analyst
6. Hilltop Securities — Risk Analysis Associate
7. Zelis — Contract Analyst I
8. Texas Oncology / US Oncology — Healthcare Operations Business Analyst
9. American Airlines — Strategic Planning and Analysis
10. Citi — Loan Documentation and Processing Associate Analyst

HCSC Privacy Analyst is included as a refreshed existing record rather than a duplicate.
