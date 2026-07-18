# Firestore Data Analyzer — Website

Documentation, user guide, and legal pages for the [Firestore Data Analyzer](https://github.com/niknack/Chrome-Extensions) Chrome extension. Pure static HTML/CSS — no build step, no dependencies.

**Live site:** https://niknack.github.io/firestore-data-analyzer/

## Pages

| Path | Purpose |
|---|---|
| `index.html` | Landing page: positioning, feature overview, quick start |
| `guide/` | Full user guide (linked from the extension's Help) |
| `privacy.html` | Privacy policy (URL used in the Chrome Web Store listing) |
| `terms.html` | Terms of service |

## Deploying (GitHub Pages)

One-time setup: **Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`**. Every push to `main` then redeploys automatically. `.nojekyll` disables Jekyll processing so files are served as-is.

## Editing

All styling lives in `assets/style.css`. Links are relative, so the site works at any base path (github.io project path or a custom domain).

To-do:

- [ ] Add real screenshots to the landing page and guide
- [ ] Add Chrome Web Store install link once the listing is live
