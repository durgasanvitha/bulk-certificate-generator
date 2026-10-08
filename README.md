# Bulk Certificate Generator

A browser-based bulk certificate generator.

## Run
1. Extract this folder.
2. Open `index.html` in Chrome/Edge.
3. Upload a PNG/JPG certificate template.
4. Upload CSV/XLSX recipient data.
5. Select the Name column and position the name.
6. Preview a recipient.
7. Generate a ZIP containing individual PDFs.

No server is required. The app uses CDN libraries for XLSX, jsPDF and JSZip, so internet access is needed when first opening the page.

## Recommended spreadsheet
Name, Role, Event, Date, Department, CertificateID

The current implementation renders the selected Name field onto the template. It is intentionally generic and does not hardcode any particular event.
