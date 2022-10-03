# Time-Series-Analysis-OPEC-Crude-Oil-Price
## Time Series Analysis of OPEC Crude Oil Price data collected from Nasdaq.

## Project Goals:
- Collecting time series data with API
- Analyzing time series data to forecast crude oil prices

## Data Sources:
1. OPEC crude oil price
The time series data is publicly available on https://data.nasdaq.com/

## Limitations:
There are gaps in the time series data as weekend data is not present.

## Tools/Skills/Procedures
**Python**
- Using APIs to collect data
- Data wrangling and data cleaning
- Deriving new variables
- Time series analysis
-- Smoothing time series data
-- Decomposing the time series data
-- Dickey Fuller stationarity test
-- Differencing to reduce autocorrelation

## Findings:
As there is too much autocorrelation in the time series data, the price of crude oil can not be forecasted with reliability.

## Next steps:
We can try to forecast the price of crude oil prices by repeating the same analysis on the data from only the recent years to see if there is a different result.







