# n7m

A tiny single-page numeronym generator — turns words into abbreviations like `internationalization` → `i18n`.

No build step, no dependencies: `index.html` is the whole app.

## Run locally

Open `index.html` in a browser, or serve it:

```sh
python3 -m http.server
```

## Deploy

Push to `main`; `.github/workflows/deploy.yml` publishes `index.html` to GitHub Pages automatically. Enable Pages for the repo once, with source set to "GitHub Actions".
