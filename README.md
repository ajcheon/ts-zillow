# Zillow house price predictions using time series techniques

Final project for MSDS 604 Time Series Analysis

## Team members
  - Andy Cheon
  - Roja Immanni
  - Lin Meng
  - Kevin Wong

## Goal
Our goal is to forecast the median sold price of all homes in California from January 2016 through August 2017 by month 
(20 forecasted values).

## Dataset
The Zillow dataset consists of four variables:
  - Median rental price of all houses in California
  - Median mortgage rate
  - Unemployment rate
  - Median sold price of all houses in California (_target_)

## Methods
We use a variety of time series methods, including SARIMA, SARIMAX, and VAR models. We also perform extensive EDA and 
differencing to investigate any trends and seasonality present in the data. We find that a SARIMA (1, 1, 2) x (0, 1, 2, 12) 
model achieves the lowest validation RMSE (root mean squared error) and generate our final predictions with this model.

