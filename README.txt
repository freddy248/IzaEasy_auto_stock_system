# AutoSpares Pro — GitHub Pages PWA

This folder contains a ready-to-deploy Progressive Web App.
Deploy it to GitHub Pages and you can install it on your phone or PC.

## Quick Deploy

1. Create a **new public repo** on GitHub (e.g., `IzaEasyAutoSpares`).
2. Upload all files from this folder: `index.html`, `manifest.json`, `sw.js`, and the `icons/` folder.
3. In the repo settings → **Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main /root**
4. Open the Pages URL (e.g., `https://<your-username>.github.io/<repo>/`).

You should see an "Install AutoSpares Pro?" banner appear. You can also use the browser menu:
- Desktop Chrome/Edge: "Install app" or "Install AutoSpares"
- Android Chrome/Edge: "Add to Home screen"

## Notes

- Login demo accounts: `admin/admin123`, `manager/manager123`, `cashier/cashier123`.
- App works offline after the first load (thanks to `sw.js`).
- Your data is saved locally (browser storage). Use **Backup** / **Restore** to move it.
