# X FOOD TYCOON

A mobile-first 3D restaurant management game prototype, replacing the former X SURVIVAL browser prototype in this repository.

## Current playable prototype
- Three.js 3D restaurant scene with orbit camera controls
- Interactive burger preparation steps and order serving
- Cash, served-customer, stock, employee, and branch progression
- Hire chefs and cashiers
- Upgrade the grill and restaurant decor
- Automatic staff income while the game is open
- Offline earnings calculated when returning to the game
- Local browser save using localStorage
- Arabic right-to-left interface, designed for mobile screens

## Preview
Enable GitHub Pages for this repository:
1. Open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions**.
3. The workflow at `.github/workflows/pages.yml` deploys the root folder.
4. Open the published Pages URL after the workflow completes.

## Run locally
Open `index.html` through a local web server (recommended because the game loads Three.js as ES modules from a CDN). For example, use VS Code Live Server.

## Notes
- This is an early browser-playable prototype, not yet a native Android APK.
- Three.js is loaded from jsDelivr; internet access is required.
- Progress is stored locally in the browser on the same device/browser.
- AdMob is not integrated yet. Ads will be added after the game loop and platform build are stabilized.
