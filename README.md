
# 🏡 **IDX Exchange – Real Estate Forecasting & Valuation Models**

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow.svg)
![Machine Learning](https://img.shields.io/badge/ML-LightGBM%20%7C%20XGBoost-orange.svg)

A machine learning and real-estate analytics project developed during my **Data Scientist Internship at IDX Exchange**.
This repository contains automated pipelines, forecasting models, and valuation frameworks built using **CRMLS (California Regional MLS)** data.

The goal is to provide **accurate, scalable, and transparent home-price insights** for residential markets.

---

## 📌 **Project Overview**

This project builds an end-to-end real estate analytics workflow:

* Automated CRMLS data ingestion & cleaning
* Outlier detection using robust filtering methods
* Neighborhood-based features using **Haversine distance + KNN statistics**
* Price-per-square-foot forecasting using **LightGBM/XGBoost**
* Valuation models with explainability for business teams
* Reporting and visualization for clear decision-making

The models achieved:

* **R² ≈ 0.86**
* **MdAPE ≈ 7.93%**, after aggressive data cleaning and leakage control

---

## 🚀 **Key Features**

### 🔄 Data Pipeline

* Deduplication & missing-value resolution
* Price anomaly filters & trimmed distributions
* Feature engineering (distance, temporal, property metadata)

### 🧠 Modeling

* Regression pipelines with LightGBM/XGBoost
* Time-based validation to reduce future-data leakage
* Hyperparameter tuning & performance tracking

### 📊 Analytics & Visualization

* Neighborhood statistics (median PPSF, KNN pricing bands)
* Error heatmaps for under/over-pricing clusters
* Model interpretability with SHAP

---


### 📂 **Repository Structure**

```plaintext
├── IDX_Forecasting.py   # Main python model file
├── Presentation_Slides.pdf          # Final presentation for IDX Exchange
└── README.md
```
---

## 📈 **Results & Impact**

During my internship, these models improved:

* ⭐ **Forecast accuracy**, enabling more reliable valuation
* ⭐ **Pipeline consistency**, reducing manual cleaning time
* ⭐ **Interpretability**, allowing non-technical teams to use analytics confidently

These improvements supported IDX Exchange’s development of **valuation products and data-driven real estate insights**.

---

## 🛠️ **Tech Stack**

* Python · Pandas · NumPy
* LightGBM · XGBoost
* Scikit-learn
* Haversine · Geopy
* Matplotlib · Seaborn
* Jupyter

---

## 🤝 **About IDX Exchange**

*IDX Exchange is a real estate technology platform focusing on advanced MLS data solutions and valuation tools.*

---

## 📬 **Contact**

If you have questions or want to collaborate:

**Kate Le**
📍 Boston, MA
🔗 [LinkedIn](https://www.linkedin.com/in/katele01/)

