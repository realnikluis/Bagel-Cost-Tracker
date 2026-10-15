# Bagel Cost Tracker v6

Version 6 reorganizes Order History into three automatic workflow tabs while preserving all existing food-cost, sales, customer, mixed-dozen, and dashboard features.

## New in Version 6
- **Active Orders** tab: Pending and Ready orders.
- **Completed Orders** tab: Completed but Unpaid orders, plus Cancelled orders kept for recordkeeping.
- **Archive** tab: orders automatically move here once they are both **Completed** and **Paid**.
- Tab counts update automatically and respect the selected sales-history date period.
- Editing an order's status or payment state immediately moves it to the correct tab.
- No manual archive action is required.

## Existing features
- Ingredient price + package-size tracking with automatic unit conversion
- Editable packaging costs
- Recipe/batch costing and cost per bagel
- Wholesale and Direct-to-Consumer sales channels
- Dozen and half-dozen DTC options
- Mixed DTC dozens with two flavors
- Food-cost %, gross profit, and gross margin
- Multi-item order entry
- Customer profiles and order history
- Paid / Unpaid tracking
- Sales summaries and CSV exports
- All-time bagels sold dashboard tracker
- Full JSON export/import backup
- Offline-capable PWA files when hosted over HTTPS

## Updating GitHub Pages
Replace the files in your existing GitHub repository with the files from this folder. Keep `index.html`, `manifest.webmanifest`, and `service-worker.js` at the repository root and keep the `icons` folder beside them. Commit the changes to the same branch.

Version 6 keeps the same browser storage key (`bagel-cost-tracker-v1`), so your existing ingredients, recipes, customers, and saved orders remain on the device after the update.

## Data note
Data is stored locally in each browser/device. Export a JSON backup regularly. Cloud sync is not included yet.
