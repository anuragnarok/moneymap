# MoneyMap

A mobile-first personal finance PWA for India (INR).

## Privacy
- Financial entries are stored locally in the browser using localStorage.
- No bank credentials, card numbers, transaction data, or backups belong in this repository.
- Export a JSON backup from the app and keep it private.

## Source bundle
Upload `MoneyMap_v0.2_source_and_docs.zip` to the repository root. The archive contains the app in a `MoneyMap/` folder. The Pages workflow extracts it and publishes the app.

## Deploy
GitHub Actions publishes the contents of `MoneyMap/` to GitHub Pages. In repository Settings → Pages, set Build and deployment source to **GitHub Actions**.

## iPhone
After deployment, open the Pages URL in Safari → Share → Add to Home Screen.

## Important
This is a manual-entry budgeting aid, not a bank-connected financial product. Verify figures against bank/card statements. See `MoneyMap/README.md` and `MoneyMap/PRODUCT_SPEC.md` for details.
