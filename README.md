# PantryPicks

Weekly meal and shop optimiser for Woolworths, Coles and Aldi. Live at
https://pantrypicks.app

- `public/` — the deployed app (single-file PWA + prices.json + manifest/sw/icons)
- Any push to `main` auto-deploys to Cloudflare via the GitHub Action
- `public/prices.json` is updated by a scheduled price-refresh task; user price
  edits made in the app always outrank these values on-device

Canonical project notes live in the owner's Claude project.
