# NamRA Post Clearance Audit Dashboard (Prototype)

## Included
- `index.html`: single-file dashboard with HTML, CSS, JavaScript and Chart.js.
- Executive overview with KPI cards, assessment/recovery trend, and case status chart.
- Audit register with search and filters.
- Financial analysis for assessed, recovered and outstanding balances.
- CSV export and browser print / Save as PDF.
- Responsive layout for desktop and mobile.

## Run locally
1. Download and extract `namra_pca_dashboard.zip`.
2. Open the `namra_pca_dashboard` folder.
3. Double-click `index.html` to open it in a modern browser.
4. Internet access is required for Chart.js to load from its CDN. The tables and core layout still appear if the CDN is unavailable, but charts won't render.

Optional local server:
- Open a terminal in the folder and run `python -m http.server 8000`
- Visit `http://localhost:8000`

## Important data and security notes
- All audit records and financial values are fictional illustrative data.
- This is a front-end prototype only. Data changes are held in browser memory and reset on refresh.
- Do not enter real taxpayer, customs, or confidential government data into this prototype.
- Before official use, have NamRA IT/security teams approve the architecture, authentication, authorization, audit logging, hosting, backups, and database access.
- “Outstanding” is a simplified calculation: assessed minus recovered. It does not include appeals, adjustments, write-offs, interest, penalties, or payment plans.
- The prototype intentionally does not show operating expenses because no approved expenditure dataset or definitions were supplied.
