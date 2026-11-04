# NYC Rental Market Analytics

A Power BI portfolio project by Arthur Fay. The report tracks New York City rental listings from February 2025 through May 2026 and compares neighborhood opportunities for May 2026.

## Explore the project

- **[Open the browser lab](https://arthur-fay.github.io/lab/nyc-rentals/).** Drag the rent chart to see a monthly snapshot, select a borough to compare trends, or search the May 2026 neighborhood scores and inspect their components.
- **[Read the lab source](https://github.com/arthur-fay/arthur-fay.github.io/tree/main/lab/nyc-rentals).** See the static JavaScript companion and the exported data used by the charts.
- **[Open the original Power BI report](#open-and-refresh).** Download the report package for Power BI Desktop and the source tables.

## What the report shows

- **Executive Overview** covers asking and effective rents, monthly trends, concessions, and comparisons across all five boroughs.
- **Neighborhood Opportunities** compares the top neighborhoods by composite score. The May 2026 scoring dataset covers 94 neighborhoods in four boroughs. Staten Island appears in the executive comparisons.

In May 2026, Manhattan had the highest median asking rent ($4,795), while the Bronx had the highest share of listings with concessions (21.1%).

## Open and refresh

Download and extract the [Power BI project package](./nyc-rental-market-analytics-github.zip). It contains the report and 21 source CSVs.

1. Open `NYC_Rental_Market_Analytics_Portfolio.pbix` in Power BI Desktop to view the saved report.
2. To refresh on a different computer, update the CSV source paths in Power Query to point to the corresponding files in `data/`. The report retains the original author's Windows paths.
3. See `data/POWER_BI_IMPORT_NOTES.txt` for coverage notes and `data/export_file_manifest.csv` for the source file inventory.

The report attributes the source data to FirstMover NYC Open Data. The May listing export includes listing-level locations and URLs.
