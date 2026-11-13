# PocketBudget

<p align="center"><img src="assets/readme-banner.svg" alt="PocketBudget animated banner" width="100%"></p>

A private, offline-first personal budget planner. Track income and expenses, understand your monthly balance, and keep an exportable copy of your data.

## Features
- Add income and expense transactions with category and date
- Monthly totals for income, expenses, and balance
- Transaction history with delete controls
- CSV export for spreadsheets
- JSON backup and restore
- Local browser storage; no account, backend, analytics, or external JavaScript dependencies
- Responsive dark interface

## Run it
1. Download **Code → Download ZIP** and extract the folder.
2. Open `index.html` in a modern browser.
3. Add your first transaction. No package manager or installation is required.

Optional local server: run `python -m http.server 8000` in the project folder, then open `http://localhost:8000`.

## Data & privacy
Transactions stay in this browser's local storage. Clearing browser data can erase them; use **Backup JSON** regularly. CSV export is available for spreadsheets. The default currency is USD in this starter version.

## License
MIT — see [LICENSE](LICENSE).
