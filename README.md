# Hotel SDS Virtual Binder - GitHub Pages

This folder is a free static SDS virtual binder.

## Files

- `index.html` = the public SDS search page.
- `sds-data.json` = the SDS database.
- `.nojekyll` = tells GitHub Pages to publish the files as-is.

## How to publish on GitHub Pages

1. Create a GitHub account or use an existing one.
2. Create a new public repository, for example: `sds-binder`.
3. Upload these files:
   - `index.html`
   - `sds-data.json`
   - `.nojekyll`
4. Go to the repository settings.
5. Go to **Pages**.
6. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
7. Save.
8. GitHub will give you a URL like:
   - `https://YOUR-USERNAME.github.io/sds-binder/`
9. Create a QR code that points to that URL.

## How to update SDS records

Open `sds-data.json` and edit the records.

Example record:

```json
{
  "chemical": "Greasestrip Plus",
  "vendor": "ECOLAB",
  "purpose": "Degreaser",
  "area": "Kitchen",
  "sdsUrl": "https://example.com/sds.pdf",
  "revisionDate": "2026-01-01",
  "status": "Active",
  "notes": "Official vendor SDS."
}
```

Important:
- Use official SDS links from vendors whenever possible.
- If you host PDFs in Google Drive, make sure the file is shared as "Anyone with the link can view."
- Verify every link from a phone before printing the QR.
- Keep a printed or offline backup SDS binder for emergencies.
