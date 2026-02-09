## UK Study & Work Sponsorship Analytics Dashboard ##

## Project Overview ##

This project presents an interactive UK Study & Work Sponsorship Analytics Dashboard developed using Microsoft Power BI, SQL Server, and Advanced DAX. The dashboard analyzes historical sponsorship data for study and work visas (2010–2023) using real-world datasets published by the UK Government via Data.gov.au.

The goal of the dashboard is to uncover trends, patterns, and insights related to migration for education and employment, supporting data-driven decision-making for researchers, policymakers, and institutions.

## Data Sources ##

- UK Government Open Data (via Data.gov.au)

- Study Sponsorship datasets (CAS_D01, CAS_D02)

- Work Sponsorship datasets (CoS_D01, CoS_D02)
  

## Tools & Technologies ##

- Microsoft SQL Server – Data storage, cleaning, and merging

- T-SQL – Data type conversion, transformations, and consolidation

- Microsoft Power BI – Data modeling, visualization, and reporting

- DAX – Time intelligence, YoY growth, extension rates, and measures
  

## Methodology ##

- Imported raw sponsorship datasets into SQL Server

- Cleaned and transformed data using T-SQL

- Merged study and work datasets into consolidated tables

- Imported cleaned data into Power BI

- Created a Date Table and advanced DAX measures

- Designed interactive visualizations and slicers
  

## Key Dashboard Features ##

- Total Study vs Work Applications by Year

- Quarterly trends with Year-over-Year growth analysis

- Top 10 nationalities by study and work sponsorship

- Repeat sponsorship applications by region (map view)

- Extension rate analysis using decomposition tree

- Applications by institution (study) and industry (work)

- Interactive slicers by year, region, and nationality
- 

## Key Insights ##

- Study sponsorship applications consistently exceed work applications

- Strong seasonal patterns driven by academic calendars

- China dominates study visas, while India leads work visas

- Europe and Asia show the highest repeat sponsorship activity

Work visa holders have a higher extension rate than study visa holders


## Conclusion ##

This dashboard demonstrates how SQL, Power BI, and DAX can transform complex migration data into meaningful insights. It highlights the dynamic nature of UK migration trends and provides a scalable foundation for forecasting, policy analysis, and further research.
