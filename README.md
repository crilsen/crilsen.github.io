# crilsen.github.io

Personal landing page served with GitHub Pages at
**https://crilsen.github.io/**

## Editing

Everything lives in a single file: `index.html` (inline CSS, no build step).

```bash
# preview locally
python3 -m http.server 8000
# open http://localhost:8000
```

## Publishing

Any push to `main` is published automatically by GitHub Pages.

```bash
git add -A
git commit -m "update site"
git push
```
