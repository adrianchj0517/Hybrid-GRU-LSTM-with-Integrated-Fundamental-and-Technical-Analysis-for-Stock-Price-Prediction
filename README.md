Hybrid GRU-LSTM with Integrated Fundamental and Technical Analysis for Stock Price Prediction
📌 Overview
This project implements a Hybrid GRU-LSTM model that integrates fundamental and technical analysis to enhance stock price prediction accuracy. By combining Gated Recurrent Units (GRU) and Long Short-Term Memory (LSTM) networks, the model captures both short-term patterns and long-term dependencies in stock market data.

🔥 Features
Hybrid GRU-LSTM Model: Utilizes the strengths of both GRU and LSTM for sequential stock market prediction.
Fundamental & Technical Analysis: Incorporates key financial ratios (P/E, EPS, etc.) and technical indicators (MACD, RSI, Bollinger Bands, etc.).
Deep Learning Implementation: Built using TensorFlow/Keras.
Data Preprocessing: Includes handling missing values, feature selection, and normalization.
Performance Metrics: Evaluates predictions using MSE, RMSE, and R² scores.
Backtesting & Benchmarking: Compares results with traditional stock prediction models.

📊 Dataset Preparation
Use stock market datasets with fundamental indicators (e.g., revenue, net income) and technical indicators (e.g., moving averages, RSI).
Format the dataset as a CSV file with timestamps, open, high, low, close prices, and indicators.
Store the dataset in the data/ directory.

📈 Model Architecture
The model consists of:

GRU Layer: Captures short-term dependencies in stock price movements.
LSTM Layer: Captures long-term trends and avoids vanishing gradient issues.
Dense Layers: Outputs the final stock price prediction.
📑 Results
The model is evaluated using:
✔ Mean Squared Error (MSE)
✔ Root Mean Squared Error (RMSE)
✔ R-squared Score (R²)
