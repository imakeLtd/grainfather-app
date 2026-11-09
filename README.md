# grainfather-app

Public web pages for the Grainfather app (v6) that the stores link to.

- **Only `site/` is published** (GitHub Actions → Pages, `.github/workflows/pages.yml`).
- `site/delete-account/` — the account-deletion page given to Google Play's Data safety form
  (https://imakeltd.github.io/grainfather-app/delete-account/). Its steps mirror the app's More → Account → Delete
  Account flow; change it when that flow changes.
- Context lives in the app repo (GF-2026-NS): `docs/plan/items/auth-delete-account.md`,
  `docs/plan/items/v600-store-cut-and-submission.md`.
