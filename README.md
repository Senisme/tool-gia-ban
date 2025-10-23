# Gia Bán Online — GitHub Pages

This folder is ready for GitHub Pages (Public repository).

## Deploy
1. Create a new **public** repo on GitHub (e.g., `gia-ban-online`).
2. Upload all files in this folder to the **repository root** (index.html, .nojekyll, README.md).
3. Go to **Settings → Pages** → Build and deployment
   - Source: **Deploy from a branch**
   - Branch: **main**, Folder: **/** (root)
4. Open: `https://<your-username>.github.io/<repo-name>/`

- `index.html` already includes: localStorage autosave, file JSON autosave (File System Access API), and cloud sync (POST/GET).
- HTTPS is required for File System Access (GitHub Pages is HTTPS).