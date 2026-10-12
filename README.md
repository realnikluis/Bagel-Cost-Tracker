# Bagel Cost Tracker v4

Version 4 adds an all-time bagels-sold tracker to the dashboard while preserving the order, customer, and food-cost features from earlier versions.

## Included
- Ingredient price + package-size tracking with automatic unit conversion
- Editable packaging costs
- Recipe/batch costing and cost per bagel
- Wholesale and Direct-to-Consumer sales channels
- Dozen and half-dozen DTC options
- Food-cost %, gross profit, and gross margin
- Multi-item order entry
- Customer/business name and order date
- Pending, Ready, Completed, and Cancelled order statuses
- Paid / Unpaid tracking
- Sales summaries for today, this week, this month, last 30 days, or all time
- Historical cost and selling-price snapshots for saved orders
- Sales CSV export
- Full JSON export/import backup
- Offline-capable PWA files when hosted over HTTPS

## Version 4 dashboard tracker
- The Dashboard now shows a running **All-time bagels sold** total.
- Dozen items count as 12 bagels and half-dozen items count as 6, multiplied by the quantity on each non-cancelled order.
- New orders save the bagel quantity as a historical snapshot so later menu edits do not change the recorded total.
- Existing orders are automatically counted from their saved sales item; no re-entry is required.

## Current recipes
- Plain
- Jalapeño Cheddar
- Garlic
- Everything
- Montreal Steak Seasoning

## Updating GitHub Pages
Replace the files in your existing GitHub repository with the files from this folder, keeping `index.html`, `manifest.webmanifest`, and `service-worker.js` at the repository root and the `icons` folder beside them. Commit the changes. Your existing GitHub Pages URL and installed home-screen app stay the same.

Version 4 intentionally keeps the same browser storage key as earlier versions, so your existing ingredients, recipes, packaging, sales channels, and saved orders remain on the device after the update. Customer profiles are generated automatically from those orders.

## Data note
Data is still stored locally in each browser/device. Export a JSON backup regularly. Cloud sync is not included yet.


## Customers
Customers are built automatically from the customer/business name saved on each order. The Customers tab shows order count, total sales, paid/unpaid totals, average order value, favorite products, and full order history. Customer names also appear as suggestions when entering new orders, which helps keep repeat accounts consistent.
