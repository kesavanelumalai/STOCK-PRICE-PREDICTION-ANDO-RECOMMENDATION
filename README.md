# STOCK-PRICE-PREDICTION-AND-RECOMMENDATION

# 📈 Stock Price Prediction and Recommendation System (Multi-Model AI Powered)

This repository presents a complete AI-powered stock forecasting and recommendation system. It uses multiple deep learning and hybrid models including LSTM, GRU, BiLSTM, LSTM + XGBoost, and BiLSTM + XGBoost to predict stock prices and provide actionable Buy/Sell/Hold suggestions. A mobile app built using Flutter and a backend powered by FastAPI make this system user-friendly and ready for real-time use.

---

## 🧠 Project Objectives

- Predict future stock prices using various deep learning and hybrid models
- Recommend Buy/Sell/Hold actions using AI-driven classification
- Visualize trends using technical indicators and charts
- Deploy a complete real-time app with backend API and mobile frontend

---

## 🚀 Models Used

| Model                | Type         | Strengths |
|---------------------|--------------|-----------|
| LSTM                | Deep Learning | Captures long-term patterns |
| GRU                 | Deep Learning | Efficient and fast training |
| BiLSTM              | Deep Learning | Learns from past and future |
| LSTM + XGBoost      | Hybrid        | Sequential + decision tree |
| **BiLSTM + XGBoost**| **Hybrid**    | **Best performer overall** |

---

## 📊 Evaluation Metrics

- **RMSE**: Root Mean Square Error
- **MAE**: Mean Absolute Error
- **R² Score**: Coefficient of Determination

### 🏆 Best Performing Model: BiLSTM + XGBoost

| Stock        | RMSE   | MAE   | R² Score |
|--------------|--------|-------|----------|
| HDFCBANK     | 17.84  | 11.86 | 0.9725   |
| SBIN         | 4.67   | 2.82  | 0.9998   |
| COALINDIA    | 9.13   | 6.53  | 0.9933   |
| TATAMOTORS   | 8.65   | 5.72  | 0.9892   |

---

## 🧠 Hybrid Architecture (BiLSTM + XGBoost)

1. **BiLSTM**: Learns temporal patterns from historical stock data
2. **Feature Extraction**: Hidden states passed as features
3. **XGBoost**: Performs final prediction using BiLSTM features
4. **Output**: Predicted price + Recommendation (Buy/Sell/Hold)

---

## 📲 Mobile App Features

- Built with **Flutter**
- Stock Selection Screen with 4 stocks:
  - `HDFCBANK`, `SBIN`, `COALINDIA`, `TATAMOTORS`
- Real-time predictions via **FastAPI backend**
- Shows predicted price and recommendation
- Trend visualization using **FlChart**
- 10-day candlestick charts on user request
