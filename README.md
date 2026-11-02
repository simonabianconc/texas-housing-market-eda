# Texas Housing Market Exploratory Data Analysis (2010–2014)

**[View the Full Analysis Report](https://simonabianconc.github.io/texas-housing-market-eda/Project-descriptive-analysis.html)**

Explore the complete analysis, including descriptive statistics, visualizations, key findings, and conclusions.

## Project Overview

This project presents an exploratory data analysis (EDA) of residential housing market activity in four Texas cities: **Beaumont, Bryan–College Station, Tyler, and Wichita Falls**, using monthly observations from 2010 to 2014.

The objective is to compare local housing market characteristics, examine changes over time, and identify patterns in sales activity, property prices, transaction values, and housing supply conditions.

The analysis uses **R and R Markdown**, combining descriptive statistics, data visualization, and interpretation of the observed patterns.

## Research Questions

1. How do property sales activity and its variability differ across the four cities?
2. How did sales activity evolve between 2010 and 2014, and what seasonal patterns can be observed?
3. How do median sale prices and total transaction values differ across cities, and how did prices change over time?
4. How do housing supply conditions, measured through active listings and months of inventory, differ across cities and change over time?

## Dataset

The dataset contains **240 monthly observations** covering four cities over five years, with 60 observations per city.

The eight original variables describe:

- City, year, and month
- Monthly property sales
- Total transaction volume (USD millions)
- Monthly median sale price (USD)
- Active property listings
- Months of inventory

The dataset contains no missing observations or duplicate city-year-month combinations.

**Data scope:** Historical, aggregated monthly housing market indicators used for educational and exploratory analysis.

## Tools and Methods

**Tools:** R, R Markdown, ggplot2, dplyr, knitr, and kableExtra.

**Methods:**

- Descriptive statistics and measures of variability
- City-level comparisons using boxplots and line charts
- Monthly sales trends and seasonal patterns
- Comparisons of median sale prices and transaction values
- Analysis of active listings and months of inventory

The study is descriptive and does not attempt causal inference or forecasting.

## Key Findings

- **Sales activity:** Tyler recorded the highest overall sales activity and transaction volume, approximately $2.75 billion over the five-year period. Wichita Falls recorded the lowest.
- **Sales trends and seasonality:** Sales generally increased
