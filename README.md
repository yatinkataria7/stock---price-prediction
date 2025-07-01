📈 AAPL Stock Price Prediction Using Machine Learning

This project aims to predict the stock price of **Apple Inc. (AAPL)** using a blend of technical analysis and machine learning models. It includes the full pipeline from data preprocessing, feature engineering, model training, and performance visualization.

---

## 🧠 Project Highlights

- 2 years of historical AAPL stock data
- Feature engineering with technical indicators:
  - MACD (Moving Average Convergence Divergence)
  - RSI (Relative Strength Index)
  - Bollinger Bands
- Cleaned dataset with rolling and exponential transformations
- Predictive models:
  - Linear Regression
  - Random Forest
  - ARIMA (Time Series)
  - LSTM (Deep Learning)

---

## ✅ Model Performance Summary

| Model             | RMSE     | Accuracy Estimate |
|------------------|----------|-------------------|
| Linear Regression | ~2.85    | ~95%              |
| Random Forest     | ~1.96    | ~97%              |
| ARIMA             | ~3.10    | ~94%              |
| LSTM              | ~2.40    | ~96%              |

*Performance is evaluated on test set using scaled features and true closing prices.*

---

## 📊 Technical Indicators

Each indicator is visualized using Matplotlib:
- **MACD & Signal Line**
- **RSI**
- **Bollinger Bands**
- Overlayed on the original price chart

---

## 💼 Why This Project Matters (Industry Context)

Stock price prediction is a foundational task in algorithmic trading, investment research, and portfolio optimization. This project showcases how to:

- Apply technical indicators to financial time series
- Train and validate models to forecast future stock prices
- Visualize and compare model outputs
- Integrate machine learning in quant-style research

The use of LSTM and ARIMA allows for both traditional and modern forecasting techniques, reflecting real workflows used in hedge funds, research desks, and trading firms.

---

## 🛠️ Requirements

Install dependencies using:
```
pip install -r requirements.txt
```

---

## 📁 Repository Structure

```
📦 AAPL_Stock_Prediction/
├── AAPL_clean.csv                     # Cleaned input data
├── AAPL_Stock_Prediction.ipynb        # Main Jupyter notebook
├── /images                            # Saved plots and charts
├── model_outputs/                     # Model predictions
├── summary_report.pdf                 # Project summary report
├── requirements.txt                   # Required libraries
└── README.md                          # This file
```

---

