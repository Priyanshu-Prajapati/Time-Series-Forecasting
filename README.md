# 📈 Time Series Forecasting

Predict future values of a time series using deep learning models like LSTM and GRU, which are ideal for sequential and temporal data. This project focuses on temperature forecasting using historical daily minimum temperatures.

---

## 🧠 Project Overview

This project uses **Recurrent Neural Networks (RNNs)**, specifically **LSTM (Long Short-Term Memory)** and optionally **GRU (Gated Recurrent Units)**, to forecast future values in a time series. The dataset used contains daily minimum temperatures in Melbourne, Australia from 1981 to 1990.

---

## 📂 Dataset

- **Name**: Daily Minimum Temperatures
- **Source**: [Kaggle](https://www.kaggle.com/datasets/shenba/time-series-datasets) or [UCI Repository](https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv)
- **Features**:
  - `Date`: Timestamp
  - `Temp`: Daily minimum temperature in Celsius

---

## 🔧 Project Structure

time-series-forecasting/
├── time_series_forecasting_lstm.ipynb # Main notebook
├── daily-min-temperatures.csv # Dataset (optional if using URL)
├── README.md # Project overview
└── requirements.txt # Required Python packages
