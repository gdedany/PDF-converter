# Merge & Convert Images/PDFs to PDF

A **fully transparent**, client-side web app to merge images and PDFs into a single PDF. No data is logged, and everything happens in your browser—no backend involved.

![Demo](https://github.com/gdedany/PDF-converter/blob/main/demo.png?raw=true)

---

## Features

- **Fully Client-Side**: Everything runs in your browser—no data is sent to a server.
- **No Logging**: Your files are never stored, logged, or shared.
- **Drag and Drop**: Upload images (JPEG, PNG) or PDFs by dropping them anywhere.
- **PDF to Image Conversion**: PDFs are converted to images for preview and reordering.
- **Reorder or Remove**: Drag to reorder files or remove unwanted ones.
- **Merge & Download**: Combine images and PDFs into a single PDF file.

---

## How to Use

1. Open the app in your browser.
2. Drag and drop images or PDFs onto the page.
3. Reorder files by dragging them.
4. Remove files by clicking the "X" button.
5. Click "Convert to PDF" to merge and download.

---

## Installation (For Developers)

This app is distributed as pre-built files. To host it locally or on a server:

1. Download the `docs` folder.
2. Serve the files using a static server:
   ```bash
   npx serve dist
   ```
3. Open the app in your browser.
