# U.S. Housing and Income Analysis

## Overview
This project uses data from the U.S. Census Bureau's 2024 American Community Survey (ACS) 5-Year Estimates to explore the relationship between household income, home values, rent, and population across U.S. counties.

The goal is to understand how housing costs vary across the United States and how they relate to household income.

## Research Questions
- How is median household income related to median home values?
- How do rental costs vary across U.S. counties?
- Which counties have the largest populations and most housing units?
- How do income and housing costs differ across U.S. regions?

## Data
The data comes from the [U.S. Census Bureau's 2024 ACS 5-Year Estimates](https://www.census.gov/data/developers/data-sets/acs-5year/2024.html).

The project examines the following variables:

- **Population:** Total county population
- **Median Household Income:** Median income of households
- **Median Home Value:** Median value of owner-occupied homes
- **Median Gross Rent:** Median monthly gross rent
- **Housing Units:** Total number of housing units
- **Region:** U.S. Census region assigned using state FIPS codes

The analysis includes U.S. counties across the 50 states and Washington, D.C.

## Tools and Technologies
- **R** for data processing and analysis
- **tidyverse** for data cleaning and transformation
- **ggplot2** for data visualization
- **sf** and **tigris** for geographic data and county maps
- **Census API** for retrieving data

## Methods
The project retrieves county-level data from the Census API, cleans and converts variables into numeric formats, and assigns counties to U.S. regions. It then uses scatterplots and county-level maps to explore patterns in income, housing costs, population, and housing units.

## Visualizations
The project includes a scatterplot comparing median household income and median home value, along with county maps showing population, household income, home values, gross rent, and housing units.

## How to Run
1. Install R and RStudio.
2. Install the required R packages.
3. Obtain a Census API key from the [Census Bureau](https://api.census.gov/data/key_signup.html).
4. Add your API key to the R Markdown file.
5. Run the code chunks or knit the `.Rmd` file to generate the report.
