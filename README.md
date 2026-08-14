# MileSplit v0.5

MileSplit is a local-first loyalty ledger for separating Company and Personal loyalty-program balances.

## v0.5
- MileSplit branding and compact header
- Deep Teal visual direction
- Multiple loyalty programs
- English/German localization with automatic browser/phone-language detection
- Manual language override infrastructure (English/German dictionaries; automatic mode currently selected by the app)
- Flight, Hotel, Credit Card, Other Earning, Award/Redemption and Adjustment transaction types
- Latest 4 transactions on dashboard
- Full history grouped by year
- Company/Personal balance history
- iPhone form fields use 16px text to prevent iOS focus zoom
- Success confirmation after adding/editing transactions
- Program selector and Manage Programs side-by-side
- CSV export and JSON backup/restore
- v4 local data migration

## Updating GitHub Pages
Replace `index.html`, `manifest.json`, and `README.md` in the existing repository. Do not clear the browser's site data: v5 reads the `loyalty-ledger-v4` data created by v4 and migrates it into v5 storage.
