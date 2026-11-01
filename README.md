# Greece Labour Market Analysis

## Project Overview

This project analyzes the evolution of the Greek labour market from January 2004 to September 2026 using official statistical data from the **Hellenic Statistical Authority (ELSTAT)**.

The goal is to transform raw labour market data into a structured, analysis-ready dataset and develop an interactive **Power BI dashboard** highlighting historical trends, year-over-year comparisons, and key labour market indicators.

## Dataset

The repository currently contains both the original dataset and its cleaned, validated version.

- **Original Dataset:** Raw statistical data published by ELSTAT, preserved without modifications.
- **Cleaned Dataset (`data/processed/labour_market_cleaned.xls`):** Restructured and validated data prepared for analysis and Power BI integration.

Both datasets cover:

- Employment
- Unemployment
- Population outside the labour force
- Unemployment rates
- Seasonally adjusted and unadjusted statistics

**Source:** Hellenic Statistical Authority (ELSTAT)  
**Period:** January 2004 – September 2026

### Data Cleaning & Transformation

The cleaned dataset includes the following improvements:

1. Restructured the original data into a tabular, analysis-ready format.
2. Standardized dates using the `YYYY-MM-DD` format.
3. Converted population figures from thousands into individual persons.
4. Standardized unemployment rates as decimal proportions for percentage formatting.
5. Applied consistent formatting and data types.
6. Validated all 546 monthly-series records and their numerical values against the original dataset.

## Planned Development

The next stages of the project include:

1. **Power BI Data Modeling:** Create relationships, a date dimension, and DAX measures.
2. **Interactive Dashboard:** Develop visualizations of employment, unemployment, historical trends, seasonality, and year-over-year comparisons.
3. **Insights & Findings:** Identify and communicate key developments in the Greek labour market.
4. **Ongoing Updates:** Incorporate newly published ELSTAT statistics and maintain the dashboard.

## Project Status

🚧 **In Progress | Data Preparation Complete**

The original and cleaned datasets are now available in the repository. Data cleaning and validation have been completed.

The next stage focuses on building the Power BI data model and interactive dashboard. Dashboard files and analytical findings will be added as development progresses.