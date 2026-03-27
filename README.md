# 📊 Interpretable Time Series Forecasting using SARIMAX and Random Forest
### *Interpreting Model Behavior in Sequential Data*

---

## 🔍 Overview

This project presents a structured approach to time series forecasting combined with model interpretability. The goal is not only to generate accurate predictions, but also to understand how and why those predictions are made.

The workflow integrates statistical and machine learning methods, supported by explainability techniques that reveal the contribution of each feature over time.

---

## 🎯 Objectives

- Develop a reliable time series forecasting pipeline  
- Compare different modeling approaches  
- Apply feature engineering tailored to temporal data  
- Evaluate model performance using time-aware validation  
- Interpret predictions using explainability techniques  

---

## 🧠 Key Features

- Time-based feature engineering (lags, rolling statistics, trend)  
- Multiple forecasting models:  
  - Seasonal baseline model  
  - SARIMAX (statistical approach)  
  - Random Forest (machine learning approach)  
- Time series cross-validation  
- Residual diagnostics and error analysis  
- SHAP-based model explainability  

---

## 🏗️ Project Structure

```
time-series-forecasting-explainability/
│── data/                  # Input datasets
│── notebooks/             # Main project notebook
│── reports/
│   └── figures/           # Generated visualizations
│── requirements.txt       # Project dependencies
│── README.md              # Project documentation
│── .gitignore
│── LICENSE
```

---

## ⚙️ Methodology

### 1. Data Preparation
- Time series indexed and cleaned  
- Missing values handled appropriately  
- Data transformed for modeling  

### 2. Feature Engineering
- Lag features to capture temporal dependence  
- Rolling mean and variance for trend smoothing  
- Cyclical encoding for seasonal patterns  
- Trend index to capture long-term movement  

### 3. Modeling Approaches
- Baseline Model: Seasonal naïve benchmark  
- SARIMAX: Captures trend and seasonality  
- Random Forest: Learns nonlinear relationships  

### 4. Model Evaluation
- Time-based train/test split  
- Cross-validation for robustness  
- Metrics:
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  

### 5. Explainability
- SHAP values used to quantify feature influence  
- Global importance and local explanations analyzed  
- Feature contributions visualized across predictions  

---

## 📈 Visual Analysis

The notebook includes:

- Time series trend visualization  
- Seasonal decomposition  
- Autocorrelation and partial autocorrelation plots  
- Prediction vs actual comparison  
- Residual diagnostics  
- SHAP summary and waterfall plots  

---

## 📊 Key Insights

- Recent observations (lag features) strongly influence predictions  
- Seasonal patterns contribute consistently across time  
- Machine learning models capture nonlinear effects better than statistical models  
- Explainability methods provide clarity on model decision pathways  

---

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/lonely496-dev/time-series-forecasting-explainability.git
cd time-series-forecasting-explainability
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the notebook

```
jupyter notebook
```

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Statsmodels  
- SHAP  

---

## 📌 Notes

- Ensure correct dataset path before running  
- SHAP computations may take longer on large datasets  
- Results may vary slightly depending on random initialization  

---

## ✍️ Author

This project is part of a broader focus on:
- Data-driven modeling  
- System behavior analysis  
- Explainable artificial intelligence  

---

## 📜 License

This project is intended for academic and research purposes.

---

## ⭐ Project Summary

This work demonstrates that time series models can be both accurate and interpretable, making them more suitable for real-world decision-making where transparency matters.
