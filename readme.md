# TAJJ Import & Exports Website

A responsive static website based on the supplied TAJJ Import & Exports design.

## Files
- `index.html` — website structure
- `styles.css` — responsive styling and animations
- `script.js` — scroll reveal, counters, mobile menu, active navigation, back-to-top and form interaction
- `assets/website-reference.png` — original generated design reference

## Deploy on Netlify
1. Put these files in a folder.
2. Go to Netlify and choose **Add new site → Deploy manually**.
3. Drag the `tajj-import-exports` folder (or its ZIP contents) into the deploy area.
4. Your site will be live on a Netlify subdomain.
5. Add your custom domain from Netlify's domain settings.

## Deploy on Vercel
1. Create a new GitHub repository and upload these files.
2. Import the repository in Vercel.
3. Framework preset: **Other**.
4. Build command: leave empty.
5. Output directory: `.`

## Deploy on GitHub Pages
1. Create a repository.
2. Upload `index.html`, `styles.css`, `script.js`.
3. Open **Settings → Pages**.
4. Select the main branch and root folder.
5. Save.

## Before going live
Replace:
- `+91 90000 00000`
- `info@tajjexports.com`
- address if needed
- product list
- social links
- form submission logic

The product images currently use public Unsplash image URLs. For a fully self-contained site, download your preferred product images into `assets/` and change the CSS background URLs.
