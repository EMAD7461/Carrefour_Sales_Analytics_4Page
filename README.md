# Carrefour Sales Analytics

A Carrefour-branded Power BI project with an editable PBIP report, semantic model, five report pages, native visuals, theme assets, source CSV files, and a PBIX copy.

## Open the report

Open `Carrefour Sales Analytics.pbip` in Power BI Desktop. The report opens on Home, with navigation to the four analysis pages.

## Pages

1. Home
2. Sales Overview
3. Product & Category Analysis
4. Customer Analysis
5. Regional & Profitability

The analysis pages contain native Power BI visuals and slicers. Customer and location analyses exclude rows with blank customer IDs. Estimated product profitability only covers rows with matched product unit costs; it is not company net profit. Date filtering uses `Fact_Sales[InvoiceDate]` to cover the transaction period through 2025.

## Data sources

The eight CSV source files are included in the project root. The PBIP model currently points to their absolute paths in this checkout. If you clone the repository to a different folder or computer, update the `File.Contents` paths in the eight table queries before refreshing.

The `.pbi` folders contain machine-specific settings and caches and are intentionally excluded from version control.