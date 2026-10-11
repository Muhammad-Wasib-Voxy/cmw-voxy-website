# C.M.W Voxy Website

A responsive, static portfolio website for an indie game developer, built with HTML, CSS, and JavaScript.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser. For a local development server, use VS Code's Live Server extension.

## Publish for free
### GitHub Pages
1. Create a GitHub account and a new repository (for example `cmw-voxy-site`).
2. Upload all files and folders in this ZIP to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the published URL shown in Pages settings.

Alternative: Cloudflare Pages can deploy a static site by connecting a Git repository.

## Before publishing
- Replace sample game cards and descriptions with real projects.
- Update the itch.io link to your profile URL.
- Update YouTube and email links in `index.html`.
- Add actual download URLs to the relevant buttons/cards.
- Only publish files you have permission to distribute.
- The included logo is copied from your upload if available; if it is missing, add your logo as `assets/cmw-voxy-logo.png`.

## Structure
- `index.html` — page content
- `styles.css` — responsive styling and visual theme
- `script.js` — mobile navigation and current year
- `assets/` — logo and future project images
