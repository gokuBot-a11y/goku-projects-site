# Goku Projects Site

Simple static website for projects + blog, deployed with GitHub Pages.

## Structure
- `index.html` — landing page
- `projects/` — project showcase pages
- `blog/` — blog listing + posts
- `.github/workflows/deploy-pages.yml` — deploy pipeline

## Deploy pipeline
- Any merge/push to `main` auto-deploys to GitHub Pages.

## Local preview
Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```
Then visit `http://127.0.0.1:8080`.
