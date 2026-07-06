# Aloft Orlando Downtown - SDS Virtual Binder

This GitHub Pages package was generated from the uploaded SDS Master List.

## Included

- `index.html` - public SDS search page
- `sds-data.json` - database with 90 SDS records
- `expected-sds-pdf-filenames.csv` - list of expected PDF names/paths
- `.nojekyll` - allows GitHub Pages to publish files as-is
- `sds/` - folder where SDS PDF files should be uploaded

## Important next step

The SDS links in `sds-data.json` point to files inside the `sds/` folder.

Example:

```text
sds/greasestrip-plus.pdf
```

That means the matching PDF must be uploaded to GitHub with that exact name.

Use `expected-sds-pdf-filenames.csv` to rename/match your PDF files.

## GitHub Pages setup

1. Upload all files/folders to your `sds-binder` repository.
2. Go to repository **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Your site should publish at a URL like:

```text
https://loannelmarin.github.io/sds-binder/
```

## QR Code

Create the QR code pointing to the GitHub Pages URL above.

## Compliance backup

Keep a printed or offline backup available in case internet, Wi-Fi, QR scanning, or GitHub Pages is unavailable.
