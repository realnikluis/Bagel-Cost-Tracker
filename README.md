# Bagel Cost Tracker v5

Version 5 adds mixed-flavor Direct-to-Consumer dozens while preserving all existing food-cost, order, customer, sales, and dashboard features.

## New in Version 5
- The Orders & Sales tab now includes **Mixed DTC Dozen**.
- A mixed dozen is priced at the normal DTC dozen price ($22 with the current data).
- Choose **two different bagel flavors**; the app treats the dozen as **6 bagels of Flavor 1 + 6 bagels of Flavor 2**.
- Food + packaging cost is calculated from the actual two selected recipes plus the normal dozen packaging.
- Gross profit updates automatically based on that mixed cost.
- Mixed dozens count as **12 bagels** in the All-Time Bagels Sold dashboard tracker.
- Saved mixed orders store the selected flavors, selling price, and food-cost snapshot so historical results remain stable if ingredient prices later change.
- Existing single-flavor DTC dozens and half-dozens remain available.

## Existing features
- Ingredient price + package-size tracking with automatic unit conversion
- Editable packaging costs
- Recipe/batch costing and cost per bagel
- Wholesale and Direct-to-Consumer sales channels
- Dozen and half-dozen DTC options
- Food-cost %, gross profit, and gross margin
- Multi-item order entry
- Customer profiles and order history
- Pending, Ready, Completed, and Cancelled statuses
- Paid / Unpaid tracking
- Sales summaries and CSV exports
- All-time bagels sold dashboard tracker
- Full JSON export/import backup
- Offline-capable PWA files when hosted over HTTPS

## Updating GitHub Pages
Replace the files in your existing GitHub repository with the files from this folder. Keep `index.html`, `manifest.webmanifest`, and `service-worker.js` at the repository root and keep the `icons` folder beside them. Commit the changes to the same branch.

Version 5 keeps the same browser storage key (`bagel-cost-tracker-v1`), so your existing ingredients, recipes, customers, and saved orders remain on the device after the update.

## Data note
Data is stored locally in each browser/device. Export a JSON backup regularly. Cloud sync is not included yet.
