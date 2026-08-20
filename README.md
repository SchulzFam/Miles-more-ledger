# MileSplit v5.13

English-only stable release. Language selection and automatic phone-language detection are removed for now.

This release preserves the current visual design and functionality while restoring the reliable Home Screen hydration path used by the last known-good release. The Home Screen now reloads the persisted ledger on startup/pageshow/focus/visibility, uses the main MileSplit storage key first, and only falls back to legacy/other storage when necessary.

MILESPLIT_RELEASE: 5.13
