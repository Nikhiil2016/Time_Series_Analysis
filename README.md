# Time series forecasting of UK electricity fuel consumption using ARIMA model.

## Overview
This project focuses on analyzing and forecasting the United Kingdom's total fuel consumption for electricity generation using time series modeling techniques. The goal was to identify trends, seasonality patterns, and build a predictive model for future energy demand.

## Objective
1.Analyze historical fuel consumption data
2.Identify seasonal and trend components
3.Build a forecasting model
4.Evaluate prediction accuracy

## Dataset
- Source: UK Government energy datasets
- Time range: Historical monthly/quarterly records
- Variables: Fuel type, total consumption, electricity generation metrics

## Tech Stack
1.Python
2.Pandas
3.NumPy
4.Matplotlib
5.Statsmodels
6.ARIMA / SARIMA

## Methodology
1. Data Cleaning
   Handled missing values
   Converted date columns to time-index format
2. Exploratory Data Analysis
   Trend visualization
   Seasonality decomposition
3. Model Development
   ARIMA model selection
   Hyperparameter tuning
4. Evaluation

## Results
The ARIMA model successfully captured seasonality and trend components, achieving reliable short-term forecasts. The model demonstrated strong predictive capability for energy demand planning.

## Future Improvements
Include exogenous variables (weather, policy changes)
Deploy as an API

