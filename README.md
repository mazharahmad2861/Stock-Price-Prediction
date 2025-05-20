# Stock Price Prediction using LSTM 

This project demonstrates how to use a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data. We focus on Apple Inc. (AAPL) stock data sourced from Yahoo Finance.

---

##  Project Overview

Time series forecasting is a critical problem in many fields, and stock market prediction is one of the most prominent. In this project, we use an LSTM network—an advanced recurrent neural network (RNN)—to learn temporal dependencies and make predictions on future stock prices.

---

##  Dataset

- **Source:** Yahoo Finance  
- **Ticker:** AAPL (Apple Inc.)
- **Features Used:** 
  - `Open`
  - `High`
  - `Low`
  - `Close`
  - `Volume`

The data is fetched using the `yfinance` Python library.

---

## Model Architecture

- **Model Type:** LSTM (Long Short-Term Memory)
- **Layers:**
  - LSTM Layer(s)
  - Dropout Layer (to prevent overfitting)
  - Dense Output Layer
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam

---

##  Requirements

Make sure you have the following packages installed:

bash
pip install numpy pandas matplotlib yfinance scikit-learn tensorflow

### Clone the repository
git clone https://github.com/yourusername/Stock-Price-Prediction.git
cd stock-price-prediction-lstm

### Run the Jupyter notebook or Python script:
python lstm_stock_predictor.py
