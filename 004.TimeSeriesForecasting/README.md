# Time Series Forecasting with ARIMA

Time Series Forecasting means analyzing and modeling time-series data to make future decisions. Some of the applications of Time Series Forecasting are weather forecasting, sales forecasting, business forecasting, stock price forecasting, etc. The ARIMA model is a popular statistical technique used for Time Series Forecasting

## What is ARIMA?

ARIMA stands for Autoregressive Integrated Moving Average. It is an algorithm used for forecasting Time Series Data. ARIMA models have three parameters like ARIMA(p, d, q). Here p, d, and q are defined as:

1. p is the number of lagged values that need to be added or subtracted from the values (label column). It captures the autoregressive part of ARIMA.
2. d represents the number of times the data needs to differentiate to produce a stationary signal. If it’s stationary data, the value of d should be 0, and if it’s seasonal data, the value of d should be 1. d captures the integrated part of ARIMA.
3. q is the number of lagged values for the error term added or subtracted from the values (label column). It captures the moving average part of ARIMA.

# Project Details

To accomplish this, I used the Yahoo Finance API to collect the historical stock price data for the past year, and then used Python and various libraries such as pandas, yfinance, matplotlib, statsmodels, and more.

First, I plotted the closing stock prices of Google on a graph to visualize the data. I then used the seasonal decomposition method to determine if the data was stationary or seasonal. As the data was seasonal, I used the Seasonal ARIMA (SARIMA) model to forecast future stock prices.

To use the SARIMA model, I needed to determine the p, d, and q values. I found the value of p by plotting the autocorrelation of the closing price column and the value of q by plotting the partial autocorrelation plot. As for the value of d, it was determined to be 1 since the data was seasonal.

I then built the ARIMA and SARIMA models and predicted the future stock prices of Google for the next 10 days using the SARIMA model. Finally, I plotted the predicted values on a graph to compare them with the actual training data.

In everyday life, this code could be used by stock traders and investors to forecast future stock prices and make informed decisions on buying, selling, or holding their investments. Additionally, this code could be modified to work with other stocks and time periods, allowing for broader use in the stock market.