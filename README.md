# MileSplit v5.1

MileSplit is a client-side loyalty ledger for separating personal and company loyalty balances across multiple programs.

## v5.1 focus
- Compact header with program selector and settings.
- Manage loyalty programs: edit name, edit unit type, reorder, archive/restore.
- Miles & More is a normal editable program; it is not hard-coded or protected.
- Three compact Company / Personal / Total balance cards with blue/green/gold typography and borders.
- Recent transactions limited to four; full history opens in a modal.
- Company and Personal history use the same newest-first history component, filtered by ownership.
- Inline SVG icons so the PWA does not depend on emoji or external assets.
- English/German with automatic device/browser language detection.
- Local data storage plus JSON backup/restore.
- Existing common v4 storage keys are migrated on first launch when found.

## GitHub Pages
Upload `index.html`, `manifest.json`, and `icon.svg` to the site root. No build step or Jekyll is required.
