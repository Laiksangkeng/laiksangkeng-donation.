# Laiksangkeng — Bitcoin Donation Website

## Included
- `index.html` — responsive static donation page
- `bitcoin-donation-qr.png` — locally generated QR code (if present)

## Deploy free with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `laiksangkeng-donation`.
2. Upload `index.html` and `bitcoin-donation-qr.png` (if included) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/laiksangkeng-donation/`

## Important
- The page accepts Bitcoin donations directly to the public address configured in `index.html`.
- Never publish your seed phrase or private keys.
- Test the QR code and address with your own wallet before sharing the page.
- Donations are on-chain BTC only; Lightning is not enabled.
