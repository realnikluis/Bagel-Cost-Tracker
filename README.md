# Bagel Cost Tracker v1

This first production-ready version includes the five current bagel recipes and pricing supplied during setup.

## Included
- Ingredient price + package-size tracking with automatic unit conversion
- Editable packaging cost (Plastic Bag: 100 for $4.28)
- Recipe/batch costing and cost per bagel
- Wholesale and Direct-to-Consumer sales channels
- Dozen and half-dozen DTC options
- Food-cost %, gross profit, and gross margin
- Export/import backups
- Offline-capable PWA files when hosted over HTTPS

## Current recipes
- Plain
- Jalapeño Cheddar
- Garlic
- Everything
- Montreal Steak Seasoning

## Current selling prices
- Wholesale dozen: $15
- DTC dozen: $22
- DTC half-dozen: $12

## Use immediately
Open `index.html` in a browser. Data saves to that browser/device.

## Install as a web app
Host this folder on any HTTPS static host. Then open the site on your phone and use the browser's Add to Home Screen / Install App command. The included manifest and service worker allow standalone/offline use after the first load.

## Important limitation
v1 stores data locally in the browser. It does not yet sync between phone and computer or provide user accounts. Use Export regularly to keep a backup.
