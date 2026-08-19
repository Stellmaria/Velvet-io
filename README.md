# Velvet Anatomy public site

Public static website and privacy policy for Velvet Anatomy.

This repository intentionally contains only files intended for public web access. The private Velvet application, infrastructure, archive, credentials, and internal documentation are not mirrored here.

## Public URLs

After GitHub Pages is enabled with **Settings → Pages → Build and deployment → GitHub Actions** and the deployment workflow succeeds:

- Website: `https://stellmaria.github.io/Velvet-io/`
- Privacy Policy: `https://stellmaria.github.io/Velvet-io/privacy/`

## Layout

- `site/index.html` — landing page
- `site/privacy/index.html` — privacy policy
- `site/assets/` — local styles and favicon
- `site/.nojekyll` — publish as plain static files
- `site/robots.txt` — public indexing policy
- `.github/workflows/pages.yml` — validation on pull requests and deployment from `main`

Only the `site/` directory is uploaded to GitHub Pages.
