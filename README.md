# Bitcoin_Price_Predictor

## 📌 Project Overview

Bitcoin is a highly volatile cryptocurrency whose price is influenced by market trends, investor sentiment, and global economic factors. Traditional prediction methods often fail to capture its complex time-series patterns. This project uses Deep Learning models, particularly Long Short-Term Memory (LSTM) networks, to predict future Bitcoin closing prices based on historical market data.

## 🎯 Objective

• Analyze historical Bitcoin price movements
• Model time-series data using Deep Learning
• Predict future closing prices of Bitcoin
• Evaluate prediction performance using error metrics

## 📊 Dataset Description

The dataset contains historical Bitcoin market data with the following features:

• Open – Opening price of Bitcoin
• High – Highest price during the time period
• Low – Lowest price during the time period
• Close – Closing price (Target Variable)
• Volume – Total traded volume

Technical Indicators:

• Simple Moving Average (SMA)
• Exponential Moving Average (EMA)
• Relative Strength Index (RSI)
• Moving Average Convergence Divergence (MACD)

## 🧠 Deep Learning Model

• Model Used: Long Short-Term Memory (LSTM)
• Why LSTM?
   • Captures long-term dependencies in time-series data
   • Handles sequential price patterns effectively
   • Suitable for financial forecasting problems

## 🛠️ Technologies Used

• Language: Python
• Libraries & Frameworks:
   • NumPy
   • Pandas
   • Matplotlib
• Development Environment: Jupyter Notebook

## 🔍 Methodology

1) Data Collection
• Historical Bitcoin price data

2) Data Preprocessing
• Handling missing values
• Feature scaling using MinMaxScaler

3) Sequence Creation
• Transform data into time-step sequences

4) Model Training
• Train LSTM on historical sequences

5) Model Evaluation
• MAE, RMSE, MAPE

6) Prediction
• Forecast future closing prices

## 📈 Results

The LSTM model successfully learned price trends and temporal dependencies. While exact price prediction is difficult due to market volatility, the model produced accurate trend-based forecasts with reduced error rates compared to traditional ML models.
