# NeuroTrade 📈

NeuroTrade is an AI-powered stock signal prediction platform that generates Buy, Hold, and Sell signals using Machine Learning and Deep Learning models.

The project combines XGBoost, LightGBM, and LSTM models through a Stacking Ensemble architecture to improve prediction accuracy and capture both short-term market signals and long-term sequential patterns.

---

## Project Overview

The goal of NeuroTrade is to predict stock trading signals based on historical market data, technical indicators, volume patterns, and market trends.

The platform:

- Collects stock market data using Yahoo Finance
- Performs feature engineering and technical analysis
- Trains multiple ML and DL models
- Combines model predictions using a stacking ensemble
- Serves predictions through a FastAPI backend
- Displays results through an interactive frontend dashboard

---

## Architecture

Raw Stock Data
↓
Feature Engineering
↓
XGBoost Model
↓
LightGBM Model
↓
LSTM Model
↓
Stacking Meta Model
↓
Final Buy / Hold / Sell Signal

---

## Models Used

### XGBoost
Captures complex feature interactions and tabular patterns.

### LightGBM
Learns alternative decision boundaries and improves ensemble diversity.

### LSTM
Learns sequential patterns from 20-day historical windows of stock data.

### Meta Model
Combines predictions from all base models using Logistic Regression.

---

## Features

- Multi-class stock signal prediction
- Buy / Hold / Sell recommendations
- Technical indicator analysis
- Ensemble learning architecture
- Time-series aware validation
- Walk-forward cross validation
- Real-time prediction pipeline
- Interactive dashboard

---

## Technologies Used

### Programming

- Python

### Machine Learning

- Scikit-Learn
- XGBoost
- LightGBM

### Deep Learning

- TensorFlow
- Keras
- LSTM

### Data Analysis

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Backend

- FastAPI

### Deployment & Tools

- Git
- GitHub
- Joblib
- yFinance

---

## Project Structure

```text
NeuroTrade/
│
├── backend/
├── frontend/
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── notebooks/
├── README.md
└── requirements.txt
```

---

## Workflow

### Step 1
Collect stock market data using Yahoo Finance.

### Step 2
Perform data cleaning and feature engineering.

### Step 3
Generate technical indicators such as:
- RSI
- MACD
- Bollinger Bands
- ATR
- Volume Features

### Step 4
Train XGBoost and LightGBM models.

### Step 5
Build LSTM sequences using 20-day lookback windows.

### Step 6
Generate Out-of-Fold (OOF) predictions.

### Step 7
Train the stacking meta-model.

### Step 8
Evaluate model performance on unseen validation data.

### Step 9
Deploy the trained models through FastAPI and dashboard interface.

---

## Key Skills Demonstrated

- Machine Learning
- Deep Learning
- Time Series Forecasting
- Ensemble Learning
- Feature Engineering
- Financial Analytics
- Model Evaluation
- FastAPI Development
- Data Visualization
- MLOps Fundamentals

---

## Future Improvements

- Hyperparameter optimization
- Portfolio optimization module
- Sentiment analysis integration
- Real-time streaming market data
- Automated trade execution

---

## Author

**Murali Manohara** and **Om Naik**

AI Engineer | Data Scientist | Machine Learning Enthusiast
