# NHEditor

**A fast, free text and code editor that runs in your browser, with no install and no account.**

NHEditor brings the power tools of classic Windows editors to a single HTML file. Open many files in tabs,
colour-code your code, and find and replace across all of them with regular expressions. You can edit CSV
files as tables, compare two files side by side, and record macros to repeat boring edits. It works offline,
and nothing you type is uploaded anywhere.

**Try it:** https://YOUR-USERNAME.github.io/nheditor/

## Why NHEditor?

- **Nothing to install.** One file. Double-click it, or open the online version.
- **Private.** Your text never leaves your computer.
- **Real files.** In Chrome and Edge, Open and Save work directly on the files on your PC.
- **Huge files.** Open and edit files of hundreds of megabytes (tested with 500 MB) without freezing.
- **Made for power users.** Most actions have a keyboard shortcut, and you can hide any toolbar button you don't use.

## Features

**Editing**
- Tabs, drag-and-drop opening, auto-indent, auto-closing brackets, overwrite mode
- Duplicate, delete and move lines; toggle comments; indent and outdent selections
- Syntax colouring for JavaScript/TypeScript, Python, HTML/XML, CSS, JSON, Markdown, C/C++/Java/C#, SQL, shell/INI/YAML and CSV

**Large files**
- Files over 10 MB (adjustable) open in a special large-file mode that only draws what is on screen
- Edit, find, replace all, bookmark and extract in files with millions of lines
- Auto-save keeps only the changed parts, so even huge files survive a reload

**Search**
- Find / Replace window with regular expressions, escape sequences, number ranges and fuzzy matching
- Search all open tabs, search only in the selection, count matches
- Bookmark or extract every match, and save find/replace pairs to a batch list
- Filter bar that shows only the lines you care about

**CSV and data**
- View CSV, TSV, semicolon and pipe files as an editable table
- Sort by any column, column statistics (sum, average, min, max), check column counts
- Export to a Markdown table, JSON or an HTML table

**Tools**
- Sort lines (A→Z, numbers, length, reverse, shuffle, remove duplicates)
- Compare two tabs side by side, with changed characters highlighted
- Record and play back macros
- Convert case, Base64, URL encoding, HTML escaping, full width / half width
- Outline panel, live Markdown / HTML preview, character map, snippets, hex view, statistics

**Make it yours**
- 13 code fonts or any font on your PC, 8 colour schemes, your own colours
- Choose which toolbars and buttons appear, tab size, spaces or tabs, word wrap at a set column
- Export and import your settings

## Run it on your computer

1. Download `index.html` (or the whole repository as a ZIP).
2. Double-click `index.html`. It opens in your browser.
3. For its own app window on Windows, make a desktop shortcut to:
   `"C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --app="file:///C:/path/to/index.html"`

Press **F1** inside NHEditor for the full list of keyboard shortcuts.

## Contributing

Bug reports and ideas are welcome in **Issues**. To change the code, edit `index.html`,
bump the version in the `APP` block at the top of the script, and add a line to `CHANGELOG.md`.

## License

MIT. See [LICENSE](LICENSE).
