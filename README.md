# Black-Scholes-Merton Greeks Model and Option Price Prediction

This project implements a Black-Scholes-Merton model to calculate the price of European call and put options. Additionally, it uses machine learning (Random Forest) to predict option prices based on historical stock data. The project also includes time series forecasting using ARIMA to predict future stock prices, and volatility estimation from historical stock returns.

## Project Overview

The model predicts the option prices using the **Black-Scholes-Merton formula**, which requires inputs such as the stock's spot price, strike price, time to expiration, volatility, and risk-free interest rate. Additionally, machine learning techniques (Random Forest Regressor) are used to predict option prices based on historical stock data, and ARIMA models provide time series forecasting for future stock prices.

Key features of the project:
- **Black-Scholes-Merton Model**: Used for pricing European options.
- **Volatility Estimation**: Volatility is estimated based on historical stock price data.
- **ARIMA Forecasting**: Predicts future stock prices using ARIMA time series models.
- **Random Forest Model**: A machine learning model for predicting option prices (call and put options).
- **Interactive Plots**: Interactive visualizations of option prices over time.
