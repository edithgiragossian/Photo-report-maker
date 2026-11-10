# Photo Report Maker

A browser-based tool for creating A4 photo reports for property inspections and other jobs.

## Features

- Upload multiple photos using the file picker or drag and drop.
- Automatically sort photos by filename.
- Show each filename (without its extension) beneath the photo.
- Arrange six photos per A4 page.
- Add a property/job address, report number, company name, and second footer line.
- Use **Save as PDF** to open the browser print dialog and choose **Save as PDF**.

## Run locally

Open `index.html` in a modern web browser. No Python, build process, or installation is required.

## Publish with GitHub Pages

1. Create a new GitHub repository, e.g. `photo-report-maker`.
2. Upload `index.html`, `README.md`, and `.gitignore` to the repository root and commit them to the `main` branch.
3. Open repository **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
5. Wait for deployment and open the site URL shown in the Pages settings. It usually has the form `https://YOUR-USERNAME.github.io/photo-report-maker/`.

## Privacy

Photos are handled in the browser using local file object URLs. This application does not contain code to upload photos to a server. Avoid committing actual inspection photos, client addresses, or reports to a public GitHub repository.

## Notes

The **Save as PDF** button calls the browser's print dialog; it does not directly download a PDF. For best results, select A4 paper and Save as PDF in print settings.
