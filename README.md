# 🌍 Hybrid Time Series and Machine Learning Approach for AQI Prediction

A machine learning project that predicts the **Air Quality Index (AQI)** for major Indian metropolitan cities by combining **time-series analysis**, **feature engineering**, and **ensemble machine learning models**.

---

## 📖 Overview

Air pollution is one of the most significant environmental challenges affecting public health. This project develops a hybrid AQI prediction framework that compares traditional time-series forecasting with machine learning models to improve prediction accuracy.

The study focuses on three Indian metropolitan cities:

- Delhi
- Chennai
- Mumbai

The project evaluates both statistical and machine learning techniques for AQI forecasting and demonstrates that ensemble learning models outperform conventional ARIMA models.

---

## ✨ Features

- Data preprocessing
- Missing value imputation
- IQR-based outlier treatment
- Temporal feature engineering
- Seasonal feature engineering
- Lag feature creation
- Model comparison
- Cross-validation
- Feature importance analysis
- AQI prediction visualization

---

## 📊 Dataset

The dataset contains daily air quality observations including:

- PM2.5
- PM10
- NO₂
- SO₂
- CO
- O₃
- AQI

Cities included:

- Delhi
- Chennai
- Mumbai

---

## ⚙️ Machine Learning Models

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### Baseline Model

- ARIMA

---

## 🏆 Best Model

**Gradient Boosting Regressor**

Performance:

| Metric | Value |
|--------|-------|
| R² Score | **0.9719** |
| RMSE | **16.31** |
| MAE | **11.33** |
| MAPE | **9.85%** |

---

## 📈 Results

The project demonstrates:

- Ensemble models outperform linear regression.
- Gradient Boosting provides the highest prediction accuracy.
- Lag features are the most important predictors.
- PM2.5 strongly influences AQI.
- Machine learning significantly outperforms ARIMA.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Repository Structure

```
AQI-prediction-hybrid/
│
├── V2_AQI_Prediction_Clean.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Divya150107/AQI-prediction-hybrid.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
V2_AQI_Prediction_Clean.ipynb
```

Run all cells.

---

## 📷 Sample Outputs

- AQI Distribution
- Seasonal AQI Analysis
- Model Comparison
- Actual vs Predicted AQI
- Residual Analysis
- Feature Importance

---

## 🔮 Future Work

- Weather parameter integration
- Real-time AQI prediction
- LSTM-based forecasting
- Explainable AI (SHAP)
- Deployment using Streamlit

---

## 👩‍💻 Authors

- Divya Sree P

M.Sc. Data Science  
Vellore Institute of Technology
