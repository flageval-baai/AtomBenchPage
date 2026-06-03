# ATOM-Bench Page

Static homepage for ATOM-Bench. The site is intentionally build-free so it can be deployed with GitHub Pages Actions.

## Local preview

Open `index.html` directly in a browser, or run a static server:

```bash
python3 -m http.server 8000
```

## GitHub Pages deployment

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to `main` or `master`, or manually run the `Deploy static site to GitHub Pages` workflow.

Update the placeholder links in `index.html` when the paper, code, dataset, and videos are public.
