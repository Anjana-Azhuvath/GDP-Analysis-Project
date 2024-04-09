# Term Spread-Analysis-Project

## Overview
This project is a comprehensive analysis of GDP (Gross Domestic Product) time series data. The goal is to explore trends, patterns, and insights that can be derived from historical GDP data for various countries and regions.

## Data Sources
The dataset used in this project was obtained from the Federal Reserve Economic Data. The data covers Quaterly GDP values and ten year treasury bill rates from 1976 to 2023.

## Project Structure

### Forecast Models:
Three forecasting models are implemented: ARIMA, DLM, and ARDL.
The auto.arima function is used to fit an ARIMA model to the GDP data.
The dlm function is employed to fit a dynamic linear model.
The ardl function is used to fit an ARDL model.
Summary statistics for each model are generated.
Rolling Forecast:

### Rolling forecasts are performed for each model using a loop.
The loop iterates over the data, fitting the model to a subset of the data and forecasting the next observation.
Forecasts are generated using ARIMA, DLM, and ARDL models.
The results of rolling forecasts are stored in matrices.

### Plotting Out-of-Sample Forecasts:

The out-of-sample forecasts obtained from the rolling forecast are plotted using the autoplot function.

### Calculating Metrics:

The mean squared error (MSE) and root mean squared error (RMSE) are calculated for each model.
Model accuracy metrics are generated using the accuracy function.
Summary of Models:

Summary statistics, such as AIC, BIC, and coefficient significance, are presented for each model.
Model performance is compared, and the best-performing model is identified.
Additional Calculations:

Some additional calculations are performed, possibly related to evaluating model performance or conducting further analysis.
