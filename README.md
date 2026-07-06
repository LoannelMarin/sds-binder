# Aloft Orlando Downtown - SDS Virtual Binder

This package is ready for GitHub Pages.

## What is included

- `index.html` - the SDS search page.
- `sds-data.json` - the SDS database generated from the master list.
- `sds/` - the SDS PDF files renamed with clean file names.
- `matching-report.csv` - matching report between the master list and the uploaded PDF folder.
- `qr-sds-binder.png` - QR code for `https://loannelmarin.github.io/sds-binder/`.
- `.nojekyll` - required so GitHub Pages publishes the files as-is.

## Upload to GitHub

1. Extract this ZIP on your computer.
2. Open your GitHub repository: `sds-binder`.
3. Use **Add file > Upload files**.
4. Drag and drop these items from the extracted folder:
   - `index.html`
   - `sds-data.json`
   - `matching-report.csv`
   - `qr-sds-binder.png`
   - `.nojekyll`
   - the entire `sds` folder
5. Click **Commit changes**.
6. Go to **Settings > Pages**.
7. Set:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
8. Save and wait a few minutes.

Your expected site URL is:

https://loannelmarin.github.io/sds-binder/

## Important matching notes

The uploaded SDS folder contained 89 PDF files for 90 master list records.

Corrections made automatically:

- Master #29 Zep Carpet Shampoo was found in a PDF originally labeled #32.
- Master #41 WD-40 was found in a PDF originally labeled #40.
- Master #66 DAP Kwik Seal Plus Premiun was found in a PDF originally labeled #65.

Missing:

- Master #85 DrainGel - no PDF was found in the uploaded SDS.zip.

## QR note

Before printing/posting the QR, open the GitHub Pages URL from a phone and confirm that the page loads and several PDFs open correctly.

## Emergency backup

Keep one printed or offline SDS backup available in case internet, Wi-Fi, power, QR scanning, or GitHub Pages is unavailable.
