# Indusha & Anjana — Wedding Invitation

Static site, ready for GitHub Pages. No build step.

## Deploy on GitHub Pages
1. Create a new repository on GitHub (e.g. `anjanaindusha`).
2. Upload the contents of this folder (or run the git commands below).
3. In the repo go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

```bash
git init
git add .
git commit -m "Wedding invitation site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Tip: naming the repo `<your-username>.github.io` publishes it at `https://<your-username>.github.io/`.
