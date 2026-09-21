# ViralShotAI landing page

Official static landing page for ViralShotAI.

## Production links

- Checkout: https://pay.hotmart.com/M107652196N
- GitHub Pages: https://alonsonavarretefl-sudo.github.io/viralshootia/

## Structure

- `index.html` — complete bilingual landing page
- `assets/` — optimized product and before/after images
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment
- `.nojekyll` — serves the static files without Jekyll processing

## Meta Ads setup

Before launching ads, add the real Meta Pixel ID to `CONFIG.metaPixelId` near the bottom of `index.html`. The page is already prepared to record `PageView`, `ViewContent`, and `InitiateCheckout`. Configure `Purchase` through Hotmart after payment confirmation; do not fire it from the landing page.

UTM parameters from Meta Ads are automatically carried into the Hotmart checkout URL.
