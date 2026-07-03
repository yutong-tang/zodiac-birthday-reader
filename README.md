# 星河生日仪表盘 — static website

This folder is ready for GitHub Pages.

## Option A: publish from a repository root

1. Create a GitHub repository.
2. Upload `index.html` from this folder to the root of the repository.
3. Go to repository **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

Your site will usually be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Option B: publish from a `/docs` folder

If you want to keep source files separate, rename this folder to `docs`, commit it,
then choose `main` + `/docs` in GitHub Pages settings.

## Important note

GitHub Pages hosts static websites only. That is why this public version uses
`index.html` directly instead of the local Python server in `vibetest.py`.
