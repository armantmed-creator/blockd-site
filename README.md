# blockdvpn.com — Blockd website

Static site. No build step. Legal entity: EVI Holdings, LLC.

## Files
index.html · privacy.html · terms.html · accessibility.html · style.css · 404.html · CNAME · robots.txt · sitemap.xml

## Before launch
- Make sure support@blockdvpn.com is a working inbox.
- When the app is live, change the two "Coming soon to the App Store" buttons in index.html to "Download on the App Store" and point them at your App Store link.

## Deploy to GitHub Pages
1. github.com → New repository → `blockd-site`, Public → Create.
2. "uploading an existing file" → drag in every file in this folder → Commit.
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Settings → Pages → Custom domain → `blockdvpn.com` → Save.
5. At your domain registrar, set DNS (and delete any parking/forwarding records on @):
   - A @ → 185.199.108.153
   - A @ → 185.199.109.153
   - A @ → 185.199.110.153
   - A @ → 185.199.111.153
   - CNAME www → <your-github-username>.github.io
6. When the DNS check turns green, tick **Enforce HTTPS**.

## App Store Connect URLs
- Privacy Policy: https://blockdvpn.com/privacy.html
- Terms (EULA): https://blockdvpn.com/terms.html
- Marketing / Support: https://blockdvpn.com/
