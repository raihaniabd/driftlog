# driftlog-terms

Public site for [Driftlog](https://github.com/raihaniabd/driftlog) — landing page, Privacy Policy, Terms of Use, and Support page. Served via GitHub Pages from this repository's `docs/` folder.

Mirror of the structure used for `deadline-pro-privacy-terms`, with the Driftlog teal/cream brand palette.

## Layout

```
docs/
  _config.yml             Jekyll site config (sets baseurl: /driftlog)
  _layouts/default.html   Shared header/footer + inline brand SVG
  assets/
    css/style.css         Brand styles (light + dark via prefers-color-scheme)
    favicon.svg           App-icon-derived favicon
  index.html              Landing page
  privacy.md              /privacy/
  terms.md                /terms/
  support.md              /support/
```

## Deploy

1. Create a public GitHub repository named **`driftlog`** under your account.
2. Push this folder's contents to that repo (the `docs/` directory must be at the root).
3. In GitHub repo settings → **Pages**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / folder `/docs`
4. After the first build (usually ~30s), the site is live at:
   - `https://raihaniabd.github.io/driftlog/`
   - `https://raihaniabd.github.io/driftlog/privacy/`
   - `https://raihaniabd.github.io/driftlog/terms/`
   - `https://raihaniabd.github.io/driftlog/support/`

If your GitHub username is not `raihaniabd`, change `baseurl` in `docs/_config.yml` to match your project URL.

## Use in the app & App Store Connect

Once live, update App Store Connect with these URLs:

| Field | URL |
|---|---|
| Privacy Policy URL | `https://raihaniabd.github.io/driftlog/privacy/` |
| Marketing URL (optional) | `https://raihaniabd.github.io/driftlog/` |
| Support URL | `https://raihaniabd.github.io/driftlog/support/` |

The in-app Privacy and Terms screens in `app/legal/` mirror this site's text. If you ever update one, update the other to match.

## Local preview (optional)

If you have Ruby + Bundler installed:

```
cd docs
bundle init
bundle add jekyll
bundle exec jekyll serve --baseurl ""
```

…then open `http://localhost:4000`. (Override `baseurl` to empty during local preview, so links resolve correctly.)
