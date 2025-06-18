# 🍸 Alcohol Consumption Analysis and Forecasting

A complete data science project to analyze and forecast alcohol consumption trends across various bars and brands using machine learning (XGBoost) and deep learning time series models (Prophet).

## 📁 Files Included

- **`Consumption Dataset.xlsx`**  
  Raw data file containing transactional alcohol consumption data including brand, type, time served, and balances.

- **`Alcohol_Consumption_Forecasting_Extended.ipynb`**  
  Jupyter notebook that performs data cleaning, exploratory data analysis (EDA), time-series forecasting using Prophet, and predictive modeling using XGBoost for multiple bars and brands.

---

## 📊 Project Features

### ✅ Data Cleaning and Preprocessing
- Converts raw datetime strings to proper datetime objects
- Extracts date, hour, weekday, and more
- Calculates net balance changes and consumption

### 📈 Exploratory Data Analysis (EDA)
- Top alcohol types and brands by consumption
- Hourly heatmaps of consumption
- Daily trend visualization per bar
- Brand-wise comparison across bars

### 🔮 Time Series Forecasting with Prophet
- Forecasts future alcohol consumption (14 days)
- Supports forecasting for **multiple bars and brands**
- Plots with forecast confidence intervals

### ⚙️ Predictive Modeling with XGBoost
- Uses lag features, rolling means, and calendar features
- Evaluates model performance with RMSE
- Ideal for real-time prediction engines

### 📦 Inventory Management Suggestions
- Calculates par level based on forecast
- Integrates lead time and safety stock

---
