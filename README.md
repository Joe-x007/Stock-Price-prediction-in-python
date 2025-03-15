# Stock Price Prediction Using LSTM

## Overview
This project implements an advanced stock price prediction model using Long Short-Term Memory (LSTM) networks. By combining historical stock data with technical indicators, the model forecasts future closing prices, demonstrating a robust approach to time-series forecasting.

## Features
- **Data Collection:** Downloads historical stock data (e.g., AAPL) from Yahoo Finance.
- **Feature Engineering:**  
  - Creates lag features (previous day’s close).
  - Computes technical indicators like 10-day & 50-day moving averages.
  - Calculates the Relative Strength Index (RSI).
- **Data Preprocessing:**  
  - Handles missing data.
  - Normalizes data using MinMaxScaler.
  - Converts data into sequential format suitable for LSTM input.
- **Deep Learning Model:**  
  - Builds a multi-layer LSTM model with dropout layers.
  - Trains the model to predict the next-day closing price.
- **Evaluation & Visualization:**  
  - Evaluates model performance using RMSE.
  - Visualizes actual vs. predicted stock prices.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   cd stock-price-prediction
