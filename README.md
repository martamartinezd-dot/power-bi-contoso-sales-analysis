# Power BI Sales Analysis – Contoso Dataset

## Project overview
This repository contains a Power BI sales analysis project developed using the ContosoSales dataset. The project demonstrates an end-to-end analytical workflow, including data preparation, modeling, DAX calculations and business-focused reporting.

The objective is to showcase analytical thinking and the ability to transform raw data into clear, insight-driven dashboards.

## Dataset
The analysis is based on the ContosoSales dataset, a sample dataset provided by Microsoft for business intelligence use cases.

## Data preparation
Data transformation was performed in Power Query Editor. Key steps included:
- Cleaning and standardizing text fields
- Creation of derived columns to apply business logic
- Product reclassification, where items containing `laptop` in the `ProductName` field were labeled as `ordenador`

## DAX logic
The project uses a combination of calculated columns and measures to implement analytical logic.

Key DAX functions applied include:
- `CALCULATE`
- `IF`
- `SWITCH`
- `RANKX`

These functions support context modification, conditional logic and product ranking.

## Reporting
The final report consists of multiple pages focused on sales performance and product analysis.  
A static PDF export of the dashboard is included in this repository for quick review.

## Access to the PBIX file
Due to GitHub file size limitations, the Power BI `.pbix` file is hosted externally.

PBIX file (read-only):  
[Google Drive link](PASTE_YOUR_LINK_HERE)

To open the file, use Power BI Desktop on Windows.

## Files included
- `dashboard.pdf`: PDF export of the final Power BI report
- `README.md`: Project documentation


