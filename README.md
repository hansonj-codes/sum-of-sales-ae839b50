# Sales Summary 374959384

This is a single-page website intended for deployment on GitHub Pages. It fetches `data.csv` from the repository root, sums the `sales` column, sets the page title to "Sales Summary 374959384", and displays the total inside the `#total-sales` element.

Features:
- Uses Bootstrap 5 from jsDelivr for styling.
- Robust CSV parsing for simple CSVs (header row required).
- Displays CSV preview and handles small irregularities.

Deployment:
1. Ensure `data.csv` is present at the repository root.
2. Push this repository to GitHub.
3. Enable GitHub Pages for the repository (Settings -> Pages -> Deploy from main branch).
4. Visit the published URL. The page will fetch `data.csv` and display the computed total.

Notes:
- The page expects a header row containing a `sales` column.
- Totals are displayed with two decimal places.

Commit: see commit_message file.