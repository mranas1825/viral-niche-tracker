# Viral Niche Tracker

Daily viral TikTok accounts — sorted by date & niche, with a monetization (1min+) check on each one.

- **Live site:** https://viraltiktoknicheai.netlify.app
- Front page shows only the latest day's accounts; use the date dropdown in the controls row to view any previous day.
- Views: By Date (AI / Clipping groups) and By Niche, with search + category + monetizable filters.

## Files
- `index.html` — the static site (all account data embedded)
- `data.json` — exported tracker data (accounts, news, trending)
- `trending.json` — daily trending niches scan
- `export_data.py` — exports the master Excel tracker into `data.json`

Data is refreshed daily from the Viral Content Tracker workbook.
