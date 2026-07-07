# ScaleCare Hub Malaysia — Website

A 6-page static site: `index.html` (Home), `services.html`, `industries.html`, `gallery.html`, `faq.html`, `contact.html`, plus shared `styles.css`.

## Before publishing
Replace these placeholders (search-and-replace across all files):
- `+60123456789` → your real phone/WhatsApp number
- `info@scalecarehub.com.my` → your real email
- Facebook and Google Maps `href="#"` links → your real URLs
- Gallery page cards → real `<img>` photos (add an `images/` folder)

## Publish with GitHub Pages

**Option A — Web UI (no git needed)**
1. Go to https://github.com/new, create a repo (e.g. `scalecare-hub`), keep it Public.
2. Click "Add file" → "Upload files", drag in all files from this folder (`index.html`, `services.html`, `industries.html`, `gallery.html`, `faq.html`, `contact.html`, `styles.css`).
3. Commit the upload.
4. Go to the repo's **Settings → Pages**.
5. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and folder to **/(root)**, then Save.
6. Wait 1–2 minutes. Your site will be live at `https://<your-username>.github.io/scalecare-hub/`.

**Option B — Git command line**
```bash
cd scalecare-hub-site
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/scalecare-hub.git
git push -u origin main
```
Then enable Pages the same way as step 4–5 above.

## Custom domain (optional)
In Settings → Pages, add your domain under "Custom domain", then create a CNAME record with your DNS provider pointing to `<your-username>.github.io`.
