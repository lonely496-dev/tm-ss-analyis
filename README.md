# Time Series Forecasting with SHAP-Based Model Interpretation using SAriMax and RF Regressor

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/License-MIT-green.svg">
  <img src="https://img.shields.io/badge/Type-Time%20Series-orange.svg">
</p>

A structured time series forecasting project that combines statistical and machine learning models w.

---

## 🔍 Project Overview

This project develops a complete forecasting workflow for sequential data and integrates interpretability methods to explain model decisions. It compares multiple approaches, evaluates forecast performance using time-aware validation, and highlights the drivers behind predictions.

---

## 🤖 Models Used

- Seasonal Naïve Model (baseline)
- SARIMAX (statistical model)
- Random Forest Regressor (machine learning model)

---

## 🧠 Techniques

- Time series decomposition
- Lag features and rolling statistics
- Time-based train/test split
- Time series cross-validation
- Residual diagnostics
- Permutation importance
- SHAP explainability

---

## 📈 Forecast Performance

<p align="center">
  <img src="figures/benchmark_forecast_interval.png" width="900">
</p>
<p align="center"><em>Forecast results with an approximate prediction interval showing model performance over time.</em></p>

---

## 📊 Feature Importance

<p align="center">
  <img src="figures/top_permutation_importances.png" width="760">
</p>
<p align="center"><em>Permutation importance ranking highlights the most influential variables driving predictions.</em></p>

---

## 🧩 Model Explanation

<p align="center">
  <img src="figures/shap_waterfall_forecast.png" width="760">
</p>
<p align="center"><em>SHAP waterfall plot explaining how each feature contributes to an individual forecast.</em></p>

---

## ⚙️ Method Summary

### Data Preparation

The time series is cleaned, indexed, and structured to maintain temporal consistency.

### Feature Engineering

Lag variables, rolling statistics, and time-based encodings capture temporal patterns.

### Modeling

Baseline, SARIMAX, and Random Forest models are compared.

### Interpretation

SHAP and permutation importance explain feature contributions and model behavior.

---

---

## 🛠️ Tools Used

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels, SHAP

---

## 🚀 Running the Project

```
git clone https://github.com/lonely496-dev/time-series-forecasting-explainability.git
cd time-series-forecasting-explainability
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Author

\*\* KP Dixit
