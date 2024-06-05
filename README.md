# Erdos2023

Used Python to web scrape 10 years of daily stock prices for AAPL, GOOG, MSFT, and AMZN from Yahoo Finance. I decomposed the closing price data to visualize trends, seasonality, and residuals. Using "auto-arima," I identified optimal model parameters (2,1,2) in 13.516 seconds. The model, split over the horizon to respect temporal structure, achieved an MSE of 11.0169.
