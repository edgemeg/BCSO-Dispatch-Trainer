# Brevard Dispatch Training — GitHub Pages Package

This package contains one home page and two current training modules:

- `/traffic-stop/` — Traffic Stop Trainer v2.9.2
- `/10-28/` — 10-28 Query Trainer v1.1

## First-time GitHub setup

1. Sign in to GitHub.
2. Create a **new public repository**. A name such as `brevard-dispatch-training` works well.
3. Open the repository and choose **Add file → Upload files**.
4. Upload **the contents of this package**, not the outer ZIP itself:
   - `index.html`
   - `.nojekyll`
   - `README.md`
   - the `traffic-stop` folder
   - the `10-28` folder
5. Commit the upload.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
8. Save.
9. GitHub will show the published Pages URL after the site builds.

Your site address will normally look like:

`https://YOUR-USERNAME.github.io/brevard-dispatch-training/`

## Updating later

You do not need to create a new site for each trainer revision.

When a trainer is updated:
- replace `/traffic-stop/index.html`, or
- replace `/10-28/index.html`

The main website address stays the same.

If a new training module is added later, create another folder with its own `index.html` and add a button for it on the root `index.html`.

## Important

All training scenario data should remain synthetic. Do not place CJIS/NCIC data or real personally identifying information in this repository, especially because the recommended GitHub Pages setup uses a public repository.
