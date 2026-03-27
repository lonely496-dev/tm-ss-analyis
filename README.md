# 📊 Time Series Forecasting with SHAP-Based Model Interpretation

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg">
  <img src="https://img.shields.io/badge/License-MIT-green.svg">
  <img src="https://img.shields.io/badge/Type-Time%20Series-orange.svg">
  <img src="https://img.shields.io/badge/Explainability-SHAP-purple.svg">
</p>

A structured time series forecasting project that combines statistical and machine learning models with explainability techniques to understand how predictions are produced and which features influence model behavior.

---

## 🔍 Project Overview

This project develops a complete forecasting workflow for sequential data and integrates interpretability methods to explain model decisions. It compares multiple approaches, evaluates forecast performance using time-aware validation, and highlights the drivers behind predictions.

---

## ✨ Key Features

- Time-based feature engineering (lags, rolling statistics, trend)
- Forecast benchmarking with proper time series validation
- Combination of statistical and machine learning models
- Model interpretation using SHAP and permutation importance
- Visual diagnostics for performance and residual analysis

---

## 🤖 Models Used

- **Seasonal Naïve Model** – baseline benchmark  
- **SARIMAX** – statistical model capturing trend and seasonality  
- **Random Forest Regressor** – machine learning model for nonlinear patterns  

---

## 🧠 Techniques Applied

- Time series decomposition (trend, seasonality, residuals)  
- Lag feature creation and rolling window statistics  
- Time-based train/test split  
- Time series cross-validation  
- Residual diagnostics and error analysis  
- Permutation feature importance  
- SHAP (SHapley Additive Explanations) for model interpretation  

---

## 📊 Selected Visual Outputs

<p align="center">
  <img src="figures/benchmark_forecast_interval.png" width="900">
</p>

<p align="center">
  <img src="figures/top_permutation_importances.png" width="760">
</p>

<p align="center">
  <img src="figures/shap_waterfall_forecast.png" width="760">
</p>

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

## 🏗️ Repository Structure

```
time-series-forecasting-explainability/
│── data/
│── notebooks/
│── figures/
│── README.md
│── requirements.txt
│── .gitignore
│── LICENSE
```

---

## 🛠️ Technologies Used

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels, SHAP

---

## 🚀 Running the Project

```
git clone https://github.com/your-username/time-series-forecasting-explainability.git
cd time-series-forecasting-explainability
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Project Value

This project demonstrates that time series models can be evaluated not only by forecast accuracy, but also by how clearly their decisions can be interpreted.
