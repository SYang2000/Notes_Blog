# Quarto Blog — Lil'Log-style

This starter emulates the **format** of Lilian Weng's blog — long-form technical posts with:
- Nav: Posts · Archive · Search · Tags · FAQ
- Right-side table of contents
- Date + (approx.) reading time
- Tags/categories
- Archive grouped by year
- A simple weekly **Log** section

## Quick start
1. Install Quarto: https://quarto.org/docs/get-started/
2. Create a GitHub repo (e.g., `shuo-notes`), then:
   ```bash
   git init && git add .
   git commit -m "init: lillog-style blog"
   git branch -M main
   git remote add origin https://github.com/<USER>/<REPO>.git
   git push -u origin main
   ```
3. GitHub Pages:
   - Settings → Pages → **Deploy from a branch**
   - Branch: `gh-pages`, Folder: `/ (root)`
4. On any push to `main`, the included GitHub Action renders and publishes to `gh-pages`.

## Local preview
```bash
quarto preview
```

## Customize
- Edit `_quarto.yml`: title, site-url, repo-url, author.
- Write posts in `posts/` and logs in `logs/`.
