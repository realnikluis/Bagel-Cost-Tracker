# Bagel Cost Tracker — v7

This GitHub Pages update adds a **Batch Calculator** while retaining all prior features in v6.

## Batch Calculator

1. Open **Batch Calculator** from the app navigation.
2. Enter the number of batches you want for each bagel flavor (e.g., Plain 3, Everything 2; leave others at zero).
3. The app automatically displays the total bagels produced, ingredient cost, a combined ingredient shopping/prep list, and each flavor’s scaled recipe.
4. You can enter fractional batches such as `0.5`, and you can copy the ingredient prep list with **Copy ingredient list**.
5. Recipe quantities and ingredient prices reflect the latest values in the Recipes and Ingredients tabs.

Packaging, labor, and utilities are **not** included in the production ingredient cost.

## Safe GitHub Pages update

Upload the **contents of this folder** to your existing GitHub repository root. Replace `index.html`, `service-worker.js`, `manifest.webmanifest`, `README.md`, and `icons/` as applicable, and commit the changes to the existing branch. The app URL and installed home-screen icon remain the same.

**Before updating**, open the existing installed app and export a JSON backup. The existing browser storage key remains `bagel-cost-tracker-v1`, so your recipes, ingredient costs, past orders, customer profiles, and sales should continue to appear after the update. The batch plan is also included in future JSON exports.

**Note:** App data is saved locally in each browser/device; GitHub hosts the code but does not sync sales data between devices.
