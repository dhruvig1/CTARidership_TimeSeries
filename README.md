## CTA Ridership Forecasting and Volatility Analysis

This project aims to develop a time-series forecasting framework for Chicago Transit Authority (CTA) ridership, combining classical statistical models and modern forecasting techniques to predict short-term transit demand and analyze volatility dynamics.

The objective is to build accurate 7-day and 30-day ridership forecasts while also examining volatility patterns in ridership returns using ARCH/GARCH models.

## Problem Statement:

1. Can daily CTA ridership be accurately forecasted for short-term (7-day) and medium-term (30-day) horizons?
2. Do classical time-series models outperform modern neural forecasting models for strongly seasonal transit data?
3. Are there volatility clustering effects in ridership returns?
4. How persistent are shocks to ridership variability?

## Modelling Approaches:
1. Time Series Forecasting Models:
   a. SARIMA
   b. Prophet
   c. LSTM

2. Volatility Modelling:
   a. GARCH

## Model Evaluation metrics:
1. Mean Absolute Error
2. Residual diagnostics
3. Ljung-Box tests to test for autocorrelation
4. Residuals normality tests

## Key Insights:
1. Strong weekly seasonality dominates CTA ridership patterns.
2. Classical time-series models (SARIMA) perform competitively against neural approaches.
3. Ridership volatility exhibits near-IGARCH behavior, indicating persistent variability.
4. Forecasting accuracy improves when seasonality is explicitly modeled.
