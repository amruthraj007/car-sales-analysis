# car-sales-analysis
Analysis of car sales data to identify key pricing factors and depreciation patterns

# Car Sales Data Analysis

## Overview
This project analyzes a comprehensive car sales dataset of 1,000 vehicles to extract meaningful business insights for an automotive retailer. Through exploratory data analysis (EDA), I've identified key factors influencing car sales prices, revealed value retention patterns across different brands, and provided actionable pricing recommendations.

## Key Findings
- Prestige rating is the strongest individual predictor of sale price (correlation 0.59)
- Fuel efficiency significantly impacts pricing (correlation 0.51), reflecting consumer preference for economical vehicles
- Toyota demonstrates superior value retention across age categories
- Luxury brands command high premiums when new but experience steeper depreciation with age
- Vehicles with high fuel efficiency maintain better value across all age segments

## Methodology
1. **Data Cleaning & Preparation**: Addressed missing values using grouped imputation methods based on car maker and year
2. **Feature Engineering**: Created new variables including car age, mileage per year, price categories, and value metrics
3. **Exploratory Analysis**: Performed univariate, bivariate, and multivariate analysis to understand relationships between variables
4. **Data Visualization**: Created visualizations to effectively communicate patterns in pricing and depreciation

## Dataset
The analysis uses a dataset of 1,000 vehicle sales records with the following attributes:
- Make and model
- Year of manufacture (2002-2024)
- Mileage (5,115-149,946 miles)
- Prestige rating (1-10)
- Fuel efficiency (15-60 units)
- Sale price ($9,255-$29,390)

## Tools & Technologies
- R Programming (tidyverse, ggplot2, dplyr)
- Data Visualization (corrplot, skimr)
- Statistical Analysis (correlation, multivariate analysis)

## Repository Structure
- `/data`: Raw and processed datasets
- `/scripts`: R scripts for data cleaning, analysis, and visualization
- `/visualizations`: Generated visualizations from the analysis
- `car_sales_analysis.Rmd`: R Markdown file containing the full analysis
