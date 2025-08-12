### Unemployment Analysis in India
## Overview

This project analyzes unemployment trends across Indian states using monthly unemployment rate data.

# It includes:

    Data cleaning

    Exploratory Data Analysis (EDA)

    Visualization (line plots, heatmaps)

    Trend decomposition

    Statistical testing for COVID-19’s impact on unemployment rates.

The goal is to identify long-term trends, seasonal patterns, and significant shifts in unemployment, and to visualize these patterns in a clear, report-ready format.
Dataset

# Source: 
    Unemployment in India.csv
# Columns:

    Region → State/UT name in India.

    Date → Date of observation (monthly).

    Frequency → Frequency of data collection (Monthly).

    Estimated_Unemployment_Rate(%) → Percentage of unemployed persons in the labour force.

    Estimated_Employed → Estimated number of employed persons.

    Estimated_Labour_Participation_Rate(%) → Percentage of people participating in the labour force.

## Project Workflow
# 1. Data Cleaning

    Removed extra spaces from column names.

    Converted Date to datetime format.

    Converted unemployment-related columns to numeric.

    Dropped rows with missing Date or essential fields.

    Sorted dataset by date for time-series analysis.

# 2. Exploratory Data Analysis

    National trend: Average unemployment across all states over time.

    Top states: Identified 5 states with highest average unemployment rates.

    Seasonal patterns: Month-by-month boxplots to reveal recurring trends.

# 3. Advanced Analysis

    Heatmap: State × Date matrix showing unemployment rate color-coded for visual comparison.

    Trend decomposition: Seasonal, trend, and residual analysis for individual states using statsmodels.

    Statistical test (t-test): Compared pre-COVID (before March 2020) and post-COVID unemployment rates.

## Key Visualizations

    National unemployment trend line

    Top states unemployment trends

    Seasonal pattern boxplot

    Heatmap of unemployment

    Seasonal decomposition plot

## Technologies Used

    Python: Data analysis & visualization

    Pandas: Data manipulation

    Matplotlib / Seaborn: Plotting

    Statsmodels: Time-series decomposition

    SciPy: Statistical testing

## Results & Insights

    Clear spike in unemployment post-March 2020 in most states, coinciding with the COVID-19 lockdown.

    Seasonal effects visible in agricultural states (e.g., higher unemployment during off-season months).

    Heatmap reveals both nationwide shocks and state-specific fluctuations.
