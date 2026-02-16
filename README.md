# Goku Notes

A clean static blog hosted on GitHub Pages.

## Structure
- `index.html` — homepage + featured article
- `blog/` — archive + post pages
- `.github/workflows/deploy-pages.yml` — auto-deploy pipeline

## Deployment
Every push/merge to `main` deploys automatically to GitHub Pages.

## Local preview
```bash
python3 -m http.server 8080
```
Then open `http://127.0.0.1:8080`.
