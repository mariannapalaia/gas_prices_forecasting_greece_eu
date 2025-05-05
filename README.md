# Gas Prices Forecasting Project
This project analyzes and forecasts gas prices in Greece and other EU countries. It involves data preprocessing in Python, with results exported for forecasting, visualization and reporting in R.

## Project Structure
`CleanedData.ipynb` – Main Python notebook for data loading and preprocessing

`IEA_Energy_Prices_Monthly_Excerpt_202410.xlsx` – Raw monthly gas price data (International Energy Agency IEA)

`daily_fuel_prices.csv` – Raw gas price data for Greece ([Greece in Figures](https://github.com/GreeceInFigures))

`QuestionsBCDE_Final_.Rmd` – R script for analysis and forecasting

## Workflow
Data Preparation (Python):

- Load `IEA_Energy_Prices_Monthly_Excerpt_202410.xlsx`

- Clean, Transform and Export results to 10 csv file for 10 EU countries respectively

- Load `daily_fuel_prices.csv`

- Clean, Transform and Export results to 2 csv files for gas prices 2022 - 2023 in Greece

Visualization and Reporting (R):

### Greece
- Forecasting (Naive, Moving Average, Exponential Smoothing, MSE, MAPE)

- Trend Analysis (Linear Regression)

- Seasonality (Holt-Winter's)

### Greece Comparison with EU Countries
- Forecasting (A/F Ratios)
