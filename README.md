# Power BI Sales Analysis – Contoso Dataset

## Project overview
This project presents an end-to-end business intelligence solution developed with Power BI, using the ContosoSales dataset as a data source. The objective is to demonstrate the complete analytical workflow, from data extraction and transformation to data modeling, DAX calculations and business-oriented reporting.

The project focuses on sales performance analysis, product categorization and ranking logic, showcasing practical use of Power Query and DAX to generate actionable insights.

## Objective
The main goals of this project are:

- Apply a complete Power BI workflow: data acquisition, preparation, modeling, visualization and reporting
- Enrich and standardize raw data using Power Query
- Implement analytical logic using DAX measures and calculated columns
- Build a structured data model aligned with analytical best practices
- Design clear and meaningful reports to support decision-making

## Dataset
The analysis is based on the ContosoSales dataset, a well-known sample dataset provided by Microsoft for business intelligence scenarios.

Main elements include:
- Sales transactions
- Product catalog
- Product categories and attributes
- Time and sales-related metrics

## Data preparation (Power Query)
Data transformation was performed using Power Query Editor. Key tasks included:

- Cleaning and standardizing text fields
- Creation of derived columns to apply business logic
- Product reclassification, where items containing `laptop` in the `ProductName` field were labeled as `ordenador` to unify terminology

These transformations improve data consistency and analytical usability.

## Data model
The data model follows a structured analytical approach:

- Separation of fact and dimension tables
- Proper relationships between sales, products and related dimensions
- Optimized model to support DAX calculations and report performance

A visual representation of the data model is included in the documentation folder.

## DAX calculations
Both calculated columns and measures were used to implement business logic and analytical insights.

Key DAX functions applied include:

- `CALCULATE`: context modification for advanced aggregations
- `IF`: conditional logic for classification and segmentation
- `SWITCH`: multi-condition business rules
- `RANKX`: product ranking based on sales performance

The combination of columns and measures ensures flexibility and performance in the analytical model.

## Reporting and visualization
The report includes multiple pages designed to analyze sales performance from different perspectives, such as:

- Overall sales overview
- Product performance and ranking
- Comparative analysis across categories

Visual elements were selected to emphasize clarity, readability and insight generation rather than decorative design.

## Documentation and assets
The repository includes additional documentation to support understanding of the project:

- Screenshots of report pages
- Data model visualization
- Explanations of key analytical decisions

## How to open the project
Download the archive .pbix. Open it with Power BI Desktop. Explore it and its visualizations.
