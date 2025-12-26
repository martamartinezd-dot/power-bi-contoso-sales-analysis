# Power BI Sales Analysis – Contoso Dataset

## Project overview
This repository presents an end-to-end business intelligence project developed with Power BI, using the ContosoSales dataset. The project demonstrates the complete analytical workflow, from data preparation and modeling to DAX calculations and business-focused reporting.

The goal is to showcase analytical thinking, data transformation skills and the ability to communicate insights through well-structured dashboards.

## Objectives
- Apply a full Power BI workflow: data acquisition, preparation, modeling, visualization and reporting
- Enrich and standardize raw data using Power Query
- Implement analytical logic using both DAX measures and calculated columns
- Design a structured data model optimized for analysis
- Build clear, insight-driven reports to support decision-making

## Dataset
The analysis is based on the ContosoSales dataset, a sample dataset provided by Microsoft for business intelligence scenarios.

Main elements include:
- Sales transactions
- Product catalog
- Product categories
- Time-related attributes

## Data preparation (Power Query)
Data transformation was performed using Power Query Editor. Key tasks included:
- Cleaning and standardizing text fields
- Creation of derived columns to apply business logic
- Product reclassification, where items containing `laptop` in the `ProductName` field were labeled as `ordenador` to unify terminology

These steps improve data consistency and analytical usability.

## Data model
The data model follows an analytical best-practice approach:
- Clear separation between fact and dimension tables
- Well-defined relationships to support analysis
- Optimized structure for DAX performance

A visual representation of the data model is available in the documentation folder.

## DAX calculations
The project combines calculated columns and measures to implement business logic.

Key DAX functions used include:
- `CALCULATE` for context modification
- `IF` and `SWITCH` for conditional logic
- `RANKX` for product ranking based on sales performance

Detailed documentation of key measures is available in `docs/dax.md`.

## Reporting and visualization
The report consists of multiple pages designed to analyze sales performance from different perspectives:
- Overall sales overview
- Product performance and ranking
- Comparative category analysis

Visuals are designed to prioritize clarity, readability and insight generation.

## Project assets
This repository includes:
- A PDF export of the final report (`docs/dashboard.pdf`)
- Screenshots of report pages and data model
- Documentation of key DAX calculations

## Access to the PBIX file
Due to GitHub file size limitations, the Power BI `.pbix` file is hosted externally.

You can download the file (read-only) here:
[Google Drive – PBIX file](https://drive.google.com/file/d/1wje4zbq0QX16o3-my_Jblv_qTY3LK4lR/view?usp=drive_link)

To open the file, use Power BI Desktop on Windows.

## How to open the project
- Download the `.pbix` file from the link above
- Open it using Power BI Desktop (Windows)
- Explore the report pages, data model and DAX logic

