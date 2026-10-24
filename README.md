# Bagel Cost Tracker — v8 (custom business logo)

This is the v7 Bagel Cost Tracker with the provided black brand logo now used in the **installed home-screen app icon**, **in-app header**, **Apple touch icon**, and **browser favicon**. All existing recipes, order/customer management, order archive, all-time bagels sold, and the Batch Calculator remain in place.

## Updating the existing GitHub Pages app

1. **First export a JSON backup** from your currently installed app, using **Export**. Download and keep the file safe.
2. Open this ZIP and the `bagel-cost-tracker-v8` folder inside it.
3. Upload the **files and folders inside that folder** to the *root of your existing GitHub repository*, replacing the previous `index.html`, `manifest.webmanifest`, `service-worker.js`, `README.md`, and icon files. **Keep the `icons` folder and its new image files.** Commit to the same `main` branch.
4. Allow the GitHub Pages deployment to finish, then close and reopen the installed app. You may need to refresh the website or reopen the app twice to activate the new offline cache.
5. **Home screen icons can be sticky:** On iPhone, if the old icon remains even though the in-app logo has changed, first **export and save a JSON backup**; removing an installed iPhone web app can erase its device-local data. Then remove the Home Screen app, visit your GitHub Pages URL in Safari, and choose *Share → Add to Home Screen*. If needed, use **Import** to restore your backup. Android may similarly require a reinstall to update its launcher icon; back up first.

The app retains the browser-local `bagel-cost-tracker-v1` storage key for backward compatibility, so publishing this update to the *same exact GitHub Pages URL* should preserve the data stored in that browser/device. Do **not** click **Reset starter data**. Device-local data does not sync across devices.

## Included icon files

- `icons/icon-192.png` — Android / PWA general icon
- `icons/icon-512.png` — Android / PWA general icon
- `icons/icon-maskable-512.png` — safe-zone variant for adaptive launchers
- `icons/apple-touch-icon.png` — iOS home-screen icon
- `icons/favicon-64.png` — desktop browser tab icon
- `icons/brand-mark.png` — logo shown in the app header
