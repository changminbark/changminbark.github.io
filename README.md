# Chang Min's Personal Portfolio

A single-page personal portfolio.

Live: [changminbark.github.io](https://changminbark.github.io/)

## Structure

```
index.html    # the entire site (HTML + inline CSS)
.nojekyll     # tells GitHub Pages to serve files as-is, no Jekyll
.github/workflows/github-pages.yml   # auto-deploy on push to main
```

## Edit & test locally

All content lives in `index.html`. To preview changes:

**Option 1 — open the file directly**

```
open index.html
```

The page works as a plain file:// URL. Fonts are loaded from Google Fonts over the network.

**Option 2 — serve it over http (recommended; matches GitHub Pages)**

```
python3 -m http.server 4321
```

Then visit `http://localhost:4321/`. Any change to `index.html` shows up on refresh — no build step.

## Deployment

Every push to `main` deploys to GitHub Pages via `.github/workflows/github-pages.yml` (using `actions/deploy-pages`). No Jekyll, no Gemfile, no `_site/` build output.

One-time setup on GitHub:

1. Repo → **Settings** → **Pages**
2. Set **Source** to **GitHub Actions**

After that, `git push` to `main` is the whole deploy flow.
