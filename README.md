# Carrefour Sales Analytics | Power BI Portfolio Project

A multi-page **Power BI portfolio project** featuring an editable Power BI Project (PBIP), semantic model, native visuals, slicers, theme assets, source CSV files, and a PBIX copy.

This is an independent portfolio / demonstration project. It is not presented as commissioned by, affiliated with, or endorsed by Carrefour.

## Report Pages

1. **Home** — report landing page and navigation.
2. **Sales Overview** — overall sales KPIs and trends.
3. **Product & Category Analysis** — product and category views.
4. **Customer Analysis** — customer-level analysis.
5. **Regional & Profitability** — regional results and estimated product profitability.

The report contains native Power BI visuals and slicers. Customer and location analyses exclude rows with blank customer IDs. Estimated product profitability only covers rows with matched product unit costs; it is not company net profit. Date filtering uses Fact_Sales[InvoiceDate] for the transaction period through 2025.

## Open the Report

- **Editable Power BI Project:** open Carrefour Sales Analytics.pbip in Power BI Desktop.
- **Power BI Desktop file:** Carrefour Sales Analytics.pbix.

## Data Model & Sources

The repository includes eight CSV source files:
- Fact_Sales.csv
- Dim_Date.csv
- Dim_Customer.csv
- Dim_Product.csv
- Dim_Category.csv
- Dim_SubCategory.csv
- Dim_Country.csv
- Dim_Location.csv

The PBIP semantic model currently points to local file paths in the original development environment. After cloning the repository to a different folder or computer, update the File.Contents paths in the eight Power Query table definitions before refreshing the model.

## Repository Contents

- Carrefour Sales Analytics.pbip — PBIP entry point.
- Carrefour Sales Analytics.Report/ — report definition and pages.
- Carrefour Sales Analytics.SemanticModel/ — semantic model definition.
- Carrefour Sales Analytics.pbix — Power BI Desktop report copy.
- CSV files — source data for the model.
- .gitignore — excludes machine-specific Power BI cache/settings folders.

## Tools & Skills Demonstrated

- Power BI Desktop and PBIP project structure.
- Semantic model organization.
- Power Query source configuration.
- Native visuals, report navigation, and slicers.
- Sales, product, customer, regional, and estimated profitability analysis.
- Technical documentation and Git version control.

## How to Open

1. Clone or download this repository.
2. Open Carrefour Sales Analytics.pbip in Power BI Desktop.
3. Update the CSV source paths in Power Query for your local folder.
4. Apply changes and refresh the model.
5. Explore the five report pages.

## Author

**Mohamed Emad**  
[GitHub](https://github.com/EMAD7461) · [LinkedIn](https://www.linkedin.com/in/mohmedemad/)
