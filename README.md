
# AgriPrice Pro – Crop Price Prediction System

AgriPrice Pro is a machine learning–based web application that forecasts monthly prices of major Indian agricultural commodities by analyzing historical price trends and rainfall patterns. The system provides an intuitive, data-driven dashboard to help farmers, traders, and policymakers make better agricultural and market decisions.

---

## Features

* **ML-based Forecasting:** Predicts crop prices for the next 6–12 months.
* **Rainfall–Price Analysis:** Integrates rainfall data to understand seasonal effects.
* **Interactive Dashboard:** Visualizes trends, top gainers/losers, and commodity-wise insights.
* **Commodity Details:** Displays historical prices, forecast ranges, and key statistical values.
* **Lightweight Web App:** Built using Flask with clean and responsive UI components.

---

## Tech Stack

**Programming:** Python

**Framework:** Flask

**Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Chart.js

**Frontend:** HTML, CSS (Materialize), JavaScript

**Database / Input:** CSV datasets of monthly crop prices & rainfall

**Data Source:** Government of India Open Data Portal (data.gov.in)

---

## Dataset Overview

Each commodity dataset contains:

* Month
* Year
* Rainfall (mm)
* Wholesale Price Index (WPI) / Price Indicator

A total of 24 major crops are included (e.g., Paddy, Wheat, Maize, Cotton, Sugarcane, Jowar, Bajra, Coconut, Mustard, Soya Bean, etc.).

---

## Methodology

1. **Data Preprocessing**

   * Cleaning, normalization, feature engineering
   * Merging rainfall and price datasets

2. **Model Training**

   * Decision Tree Regression
   * Tuned for non-linear, seasonal data patterns

3. **Forecast Generation**

   * Predicts short-term and long-term price trends
   * Computes minimum and maximum predicted price points

4. **Visualization**

   * Interactive time-series charts
   * Comparison between historical and predicted values

5. **Web Interface**

   * Flask routes provide real-time data updates
   * Commodity-wise dashboards for all available crops

---

## Future Improvements

* Integration of Random Forest / XGBoost for higher accuracy
* LSTM-based sequence models for long-term forecasting
* Addition of market API for real-time updates
* Inclusion of satellite or soil-moisture data

---



