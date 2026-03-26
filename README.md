# Project 3: COVID-19 Time Series Analysis

## Overview
This project analyzes the progression of COVID-19 using time series data from the Johns Hopkins University CSSE repository. The goal is to understand trends in confirmed cases and deaths at global and regional levels and to extract insights relevant to pandemic monitoring and response.


## Dataset
- **Source**: Johns Hopkins University (CSSE)
- **Files used**:
  - `time_series_covid19_confirmed_global.csv`
  - `time_series_covid19_deaths_global.csv`

The data contains cumulative daily counts of confirmed cases and fatalities across regions.


## Objectives
- Explore global and regional COVID-19 trends
- Identify rapid growth regions and peak fatality windows
- Apply rolling statistics to study trends and volatility
- Test stationarity using the Augmented Dickey-Fuller test
- Prepare data for forecasting using differencing


## Methodology
- Reshaped data from wide to long format and merged confirmed and deaths datasets
- Aggregated data at global and country levels
- Computed daily cases and deaths
- Applied rolling mean and rolling standard deviation
- Performed ADF tests and applied second-order differencing to achieve stationarity
- Generated insights from observed trends and volatility patterns


## Key Findings
- COVID-19 data exhibits strong weekly seasonality
- Differencing is required to stabilize the time series
- Fatalities generally lag confirmed cases
- Forecast reliability decreases during outbreak phases due to high volatility and reporting artifacts


## Tools Used
Python, pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn


## How to Run
1. Install dependencies:

## Author
Amaranth Sebeo Madise
   
