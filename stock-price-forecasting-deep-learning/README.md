# Stock Price Forecasting using Deep Learning

## Overview
This project applies deep learning models to forecast stock prices from historical time series data using CNN, LSTM, and an ensemble of both architectures.

## Problem Statement
Accurate stock price forecasting is challenging due to temporal dependencies and market volatility. This project explores deep learning models to capture short-term patterns and long-term dependencies in financial time series.

## Dataset
- Historical stock price data
- Features: Open, High, Low, Close, Volume
- Target: Future closing price

## Approach
- Time series preprocessing and windowing
- Feature scaling and sequence generation
- Model 1: 1D Convolutional Neural Network (CNN)
- Model 2: Long Short-Term Memory (LSTM)
- Model 3: Ensemble model combining CNN and LSTM outputs
- Model evaluation using Mean Squared Error (MSE)

## Results
- Ensemble model outperformed individual CNN and LSTM models
- Visualized prediction vs. actual price trends for comparison

## Technologies Used
- Python
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## How to Run
```bash
pip install -r requirements.txt
