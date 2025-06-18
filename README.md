# Stock-Price-Prediction-using-ML-Algorithms
This project explores the use of machine learning and deep learning techniques to predict the stock prices of Tata Steel, one of India’s largest steel manufacturers. It compares multiple models including Linear Regression, LSTM, and GRU to identify the most accurate forecasting approach based on historical data.

## 🔍 Project Overview

- 📈 **Objective**: To develop a robust model for forecasting Tata Steel stock prices using historical market data.
- 🔬 **Models Used**:
  - Linear Regression
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Unit (GRU)

- 🔧 **Key Techniques**:
  - Time Series Data Preprocessing
  - Feature Engineering
  - Model Training & Evaluation
  - Comparative Analysis using metrics like MSE, MAE, R²

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: 
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – visualizations
  - `scikit-learn` – regression models, evaluation metrics
  - `tensorflow`, `keras` – LSTM & GRU modeling
  - `yfinance` – historical stock data extraction

## 📊 Dataset

- **Source**: [Yahoo Finance](https://finance.yahoo.com/quote/TATASTEEL.NS/history/)
- **Accessed Using**: `yfinance` Python library
- **Features**: Open, High, Low, Close, Volume, Date, etc.

## 📈 Model Performance

- Evaluated on Mean Squared Error (MSE) and Mean Absolute Error (MAE)
- Visualized predictions vs actual prices
- GRU performed best in capturing long-term dependencies and volatility

## 📁 Project Structure

```
├── GRU_Model.ipynb
├── nural_network.ipynb
├── README.md
```

## 📅 Future Work

- Incorporate macroeconomic indicators (inflation, GDP, interest rates)
- Explore hybrid models combining LSTM + GRU
- Deploy the model via a Streamlit dashboard

## 👤 Author

**Sagar Sathiya**  
