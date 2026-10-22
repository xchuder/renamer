# Alvis Renamer

Rename in bulk. Right in your browser.

Alvis Renamer is a single-file web app for renaming many files at once. It needs no server: open `index.html` in Chrome or Edge, or host it as a static page (for example GitHub Pages).

## Features

- Add files or whole folders by browsing or drag and drop
- Set one new name for every file, or edit each file's name in the preview table
- Add a prefix and/or suffix to the existing names instead
- Map names from an Excel (`.xlsx`) or CSV file: pick the old-name and new-name columns, and files are matched by name with or without the extension. A CSV list of the added files can be exported to fill in. Legacy `.xls` files must be saved as `.xlsx` or CSV first
- Choose how duplicate names are numbered: `_1`, `-1`, ` (1)`, ` 1`, `.1` or a custom pattern, with digit count and start number
- Choose a destination folder and save renamed copies there (Chrome / Edge), keeping the subfolder structure
- Other browsers can download the renamed files as a ZIP instead

Originals are never changed or deleted, and existing files in the destination are never overwritten.

## Privacy

Everything runs locally in the browser. Files, file names and the Excel/CSV mapping table are not uploaded, sent or stored anywhere, and the app uses no cookies or tracking. Only your naming settings are kept in the browser's local storage.
