# DeerTraceR Pro — GitHub-ready build

This package is set up for GitHub Pages.

## Deploy on GitHub from iPhone or desktop
1. Create a new GitHub repository.
2. Upload every file from this folder to the root of the repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the **main** branch and **/(root)** folder, then save.
6. Wait for GitHub Pages to publish the site.
7. Open the Pages URL in Safari on iPhone and use **Share → Add to Home Screen**.

## Files included
- `index.html` — main app
- `manifest.webmanifest` — install metadata for mobile
- `sw.js` — offline caching for hosted use
- `icons/` — app icons

## Notes
- This version is intended for hosting, not direct local-file use.
- Data is saved in the browser using local storage.
- Trail-cam analysis remains mock/demo logic until a real API is connected.
