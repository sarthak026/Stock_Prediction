# Stock Analysis and Prediction

This repository contains an implementation of a Long Short-Term Memory (LSTM) model using Keras for stock analysis. The model predicts stock prices based on historical data.

## Overview

The project focuses on analyzing and predicting stock data for major tech companies, including Apple (AAPL), Google (GOOG), Microsoft (MSFT), Amazon (AMZN), and Tesla (TSLA). By leveraging historical stock information and advanced machine learning techniques, the project provides valuable insights for investors.

## Project Structure

### Data Collection

- Utilize the Yahoo Finance API to fetch historical stock data for selected companies.

### Data Analysis and Visualization

- Conduct exploratory data analysis (EDA) to understand stock characteristics.
- Visualize key metrics, trends, and relationships using matplotlib and seaborn.

### Moving Averages and Technical Indicators

- Calculate and visualize moving averages (10, 20, and 50 days) to identify trends.
- Compute the Relative Strength Index (RSI) to gauge overbought or oversold conditions.

### Risk Assessment

- Evaluate the risk associated with each stock using historical volatility metrics.
- Generate scatter plots to visualize the risk-return trade-off.

### Stock Price Prediction using LSTM

- Implement an LSTM neural network for predicting the future closing price of Apple Inc. (AAPL).
- Fine-tune hyperparameters and assess the model's performance.

## Running the Code

To replicate the analysis and run the LSTM model, follow these steps:

1. Install required dependencies: `pip install -r requirements.txt`.
2. Execute the Jupyter notebooks in sequential order.

## Key Questions Addressed

The project addresses critical questions, including changes in stock price over time, daily stock return averages, moving averages of various stocks, correlation between different stocks, risk assessment, and attempts to predict future stock behavior.

## Conclusion

The Stock Analysis and Prediction project aims to empower users with insights into historical stock trends, risk assessment strategies, and potential future price predictions. Investors can make more informed decisions in the dynamic realm of financial markets. Explore the Jupyter notebooks for detailed code implementations and analyses.
