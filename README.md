# New Brand Verification Page

This repository hosts the verification page and official PDF for the reference letter of **Bruno Azevedo Souza**.

## Files included
- `index.html` - Premium verification page (landing page) that embeds the PDF, shows contact details and the QR code.
- `letter.pdf` - Official reference letter (PDF).
- `qrcode.png` - QR code pointing to the `letter.pdf` URL.
- `logo.jpg` - Company logo (replace if needed).

## How to publish on GitHub Pages
1. Create or open repository `brunoverification/newbrand`.
2. Upload the files from this folder to the repository root:
   - `index.html`
   - `letter.pdf`
   - `qrcode.png`
   - `logo.jpg`
   - `README.md`
3. In GitHub go to **Settings → Pages**.
4. Under **Source** choose the branch `main` (or `master`) and folder `/ (root)`.
5. Save. GitHub Pages URL will be:
   `https://brunoverification.github.io/newbrand/`

## Recommended file names & URLs
- Landing page: `https://brunoverification.github.io/newbrand/` (index.html)
- PDF document: `https://brunoverification.github.io/newbrand/letter.pdf`
- QR code image: `https://brunoverification.github.io/newbrand/qrcode.png`

## Notes for IRCC verification
- Ensure `letter.pdf` is accessible without login and remains hosted for years.
- Keep the file name and URL stable.
- If you update the PDF, keep the same filename to prevent broken links.

## Optional improvements
- Add server-side validation token (not necessary for IRCC but useful).
- Add a short audit log or timestamp if you re-issue letters.

---

Generated automatically. Replace `logo.jpg` with the official high-resolution logo if needed.
