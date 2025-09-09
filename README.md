# PFAS / WRRF Reference Database

This repository hosts a public, searchable bibliography exported from Zotero.

## Files
- `data.json` — normalized JSON derived from Zotero export.
- `data.csv` — same records in CSV format.
- `index.html` — static web UI (DataTables) that reads `data.json` for search/filter/sort.

## How to Publish on GitHub Pages
1. Create a new GitHub repository (e.g., `pfas-bibliography`).
2. Upload `index.html`, `data.json`, and `data.csv` to the repository root.
3. In the repository settings, enable **GitHub Pages** (serve from the `main` branch, `/root`).
4. Visit the published URL shown in the settings (e.g., `https://<your-username>.github.io/pfas-bibliography/`).

## How to Update
- Export an updated Zotero JSON.
- Replace `data.json` (and optionally `data.csv`) with the new file(s).
- Commit and push; the website updates automatically.

## Citing & License
- Please cite the original sources using the DOI/URL provided in each entry.
- Consider adding a license (e.g., CC BY 4.0 for metadata) in this README.
