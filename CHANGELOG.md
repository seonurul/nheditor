# Changelog

All notable changes are listed here, newest first.
Versions follow MAJOR.MINOR.PATCH: bump PATCH for fixes, MINOR for new features,
MAJOR for big changes that break old settings or behaviour.

## 1.0.1 (2026-11-25)

- Auto-save is much more reliable: text is saved in two places in the browser, saved
  instantly when you reload or close the page, and large files (over 5 MB) are kept too
- New "✓ Saved" sign in the status bar; it turns red if the browser blocks saving
- Warning when auto-save is impossible (for example in a private / incognito window)
- Files opened from your PC remember where they came from, so Save still writes to the same file after a reload (Chrome / Edge)

## 1.0.0 (2026-11-23)

- First public release of NHEditor
- Tabs, syntax colouring, Find / Replace window with batch mode
- CSV table mode, Sort, Compare, Filter, Macros, Bookmarks
- Outline, Preview, Character map, Snippets, Hex view, Statistics
- Customize window: fonts, colour schemes, toolbars, editing options
