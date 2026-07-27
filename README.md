# accounting
credit and debit of each month


# Ledger Local — Offline Browser Accounting

## Run it
1. Keep all files in this folder together.
2. Open `index.html` in a modern browser. If the browser blocks WebAssembly when opening files directly, serve this folder locally with `python -m http.server` and open `http://localhost:8000`.
3. No network connection is needed after these included library files are downloaded.

## Included capabilities
- Credit/debit entry, amount, date, category, source and optional remark.
- In-form creation of categories and sources.
- SQLite database executed locally in the browser with automatic browser-storage persistence.
- Date range, category, type and remark-search reports; credit, debit, net and category totals.
- CSV report export, SQLite `.db` backup/export and import, deletion safeguards, and responsive layout.

**Privacy note:** Browser data can be removed by clearing site data; use Export backup regularly.
