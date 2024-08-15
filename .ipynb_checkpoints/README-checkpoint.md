# AAPL Stock Price Prediction And Forecasting Using Stacked LSTM -- Deep Learning

## Overview

This project involves analyzing and predicting stock prices using the AAPL dataset. The dataset contains historical stock prices of Apple Inc. (AAPL). The main goal is to build and evaluate a deep learning model to forecast future stock prices.

## Dataset

- **Source**: Historical stock price data for Apple Inc. (AAPL)
- **Features**: symbol, date, close, high, low, open, volume, adjClose, adjHigh, adjLow, adjOpen, adjVolume, divCash, splitFactor
- **Data Processing**: Normalization and reshaping for model input

## Model

- **Type**: LSTM (Long Short-Term Memory) Neural Network
- **Architecture**:
  - 3 LSTM layers
  - 1 Dense layer for output

## Key Scripts

1. **Data Preprocessing**:
   - Normalize the data
   - Split data into training and testing sets

2. **Model Training**:
   - Define and compile the LSTM model
   - Train the model with historical data

3. **Prediction**:
   - Forecast future stock prices for the next 30 days
   - Combine historical and predicted data for visualization

4. **Visualization**:
   - Plot historical and predicted stock prices
   - Include labels and figure size adjustments for clarity