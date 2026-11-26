# Changelog

All notable changes are listed here, newest first.
Versions follow MAJOR.MINOR.PATCH: bump PATCH for fixes, MINOR for new features,
MAJOR for big changes that break old settings or behaviour.

## 1.1.2 (2026-11-26)

- Fixed: selected text disappeared under the blue selection. The selection is now drawn behind
  the text, so selected words keep their full colours (light and dark themes, word wrap, tabs)
- Coloured toolbar icons in the style of classic Windows editors (can be turned off in
  Customize › Toolbar › Coloured icons)
- Darker status bar in dark mode so its text is easier to read

## 1.1.1 (2026-11-25)

- Minimal toolbar (new default): only the essential buttons are shown; everything else is under »
- Every toolbar row has a minimize button (⌃) that folds it into a thin bar; click the bar to open it again
- Toolbars never wrap onto a second line any more: buttons that don't fit move into the » menu
- Smaller, tidier toolbar buttons
- Switch between Minimal and Full toolbar in View › Minimal toolbar, the » menu, or Customize › Toolbar

## 1.1.0 (2026-11-25)

- New large-file engine: open and edit files of hundreds of MB (tested with 500 MB, 6.6 million lines)
  - Opens a 500 MB file in about 1.5 seconds; only the lines on screen are drawn
  - Full editing: typing, selection with mouse and keyboard, copy / cut / paste, undo / redo,
    indent, duplicate / move / delete lines, convert case, sort selected lines
  - Find, Replace, Replace All, Count, Bookmark and Extract work across the whole file
    (4.3 million replacements in under 2 seconds)
  - Auto-save stores only the changed parts, and the file comes back after a reload
  - Save writes the file straight to disk without building one giant copy in memory
- Files bigger than 10 MB open in large-file mode automatically (change the limit in
  Customize › General), or use File › Open in large-file mode / View › Large-file mode
- Fixed: the character width was measured with the wrong font, which made the ruler and
  highlights drift on long lines

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
