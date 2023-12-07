# Stock Price Prediction and Trading System
## Overview
This repository contains a project focused on stock price prediction and trading. It involves various tasks related to data analysis, normalization techniques, LSTM modeling, and trading strategies.

Project Tasks
# Data Visualization
Visualized minute-by-minute and day-by-day closing price series for multiple stocks.
Created complete candlestick charts with volume.
Observed occasional data issues, including unexpected jumps and missing data points in the minute-by-minute data.
## Data Normalization
Explored two data normalization methods: Min-Max scaling and Z-score normalization.
Chose Min-Max scaling due to its suitability for preserving original data relationships while ensuring a consistent range.
## Trading Scenarios
Made scenario decisions for trading, including high-frequency intra-day swing trading.
Accounted for buy-ask spreads and trading commissions.
Considered trading individual stocks or a basket of stocks from a specific industry.
## LSTM Modeling
Implemented a flexible PyTorch module for an LSTM model.
Customizable input dimensions, the number of units, and layers to suit different requirements.
## Data Loader
Developed a flexible data loader for training the LSTM model.
Included open, close, high, low, and volume data for one or more stocks.
## Model Training
Trained the LSTM model to predict future stock prices or price changes.
Reserved the last two years of data for testing.
## Trading Module
Implemented a trading module with hard-coded logical decisions for buy, hold, and sell actions.
## Testing and Evaluation
Tested the trading system on the latest years of data not part of the training dataset.
Evaluated model performance, noted how prediction errors increased with time, and assessed profitability while considering bid-ask spreads and commissions.
Compared profitability to a simple buy-and-hold strategy over the long term.
## Acknowledgments
### OpenAI for providing language model capabilities.
### Scikit-learn and PyTorch for machine learning and deep learning tools.
