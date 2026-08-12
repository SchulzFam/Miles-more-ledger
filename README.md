# Loyalty Ledger v0.4 (fixed)

This is the corrected v4 build.

### Included
- Multiple loyalty programs
- Miles & More as the default program
- Automatic migration of v1/v2/v3 transaction data into Miles & More
- Company/personal ownership
- Company/personal balance history
- Negative ownership balances allowed
- Transaction editing and deletion
- CSV export
- JSON backup/restore
- Reconciliation
- Local-first storage

### Important
The app migrates legacy transactions only once into the new v4 storage. It does not delete the old storage, so the old data remains available as a fallback.

Replace `index.html`, `manifest.json`, and `README.md` in the existing GitHub Pages repository.
