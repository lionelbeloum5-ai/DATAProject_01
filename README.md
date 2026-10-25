# E-Commerce Sales Data Analysis, Econometric Modeling & Predictive ML Pipeline

## 📌 Project Overview
This repository contains an end-to-end data science and business intelligence project developed by a data analyst. The objective is to transform raw e-commerce transaction data into actionable financial insights, econometric validation, and a predictive machine learning model.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Core language)
* **Pandas & NumPy** (Data manipulation and wrangling)
* **SciPy & Statsmodels** (Statistical testing and OLS econometric modeling)
* **Scikit-learn** (Random Forest machine learning model and evaluation metrics)
* **Matplotlib & Seaborn** (Data visualization and exploratory dashboards)

---

## 📂 Project Pipeline & Methodology

1. **Data Preprocessing & Cleaning:**
   * Missing value audit across columns.
   * Smart description imputation leveraging historical `StockCode` matches.
   * Text standardization (noise reduction, case formatting, and error correction).
   * Removal of records lacking a valid `Customer ID`.
   * Enforcement of a strict 1-to-1 bijective mapping between `StockCode` and `Description`.
   * Filtering out product returns, cancellations, and negative/zero pricing anomalies.
   * Conversion of `InvoiceDate` into a standardized datetime format.

2. **Exploratory Data Analysis (EDA):**
   * Comprehensive descriptive statistics of the cleaned dataset.
   * Comparative monthly sales analysis highlighting year-end seasonal spikes.
   * Identification of high-value customers and top-performing revenue drivers.
   * Histogram mapping of transaction basket distributions.
   * Pivot tables and geographic heatmaps tracking monthly international sales.
   * Log-scale boxplots for cross-country sales comparison while neutralizing extreme outliers.

3. **Econometric Modeling (`SciPy` & `Statsmodels`):**
   * Pearson correlation tests with p-values to prove statistical significance.
   * Ordinary Least Squares (OLS) multiple regression model to evaluate feature impacts on total revenue.

4. **Predictive Machine Learning (`Scikit-learn`):**
   * Implementation of a *Random Forest Regressor* to predict transaction amounts.
   * Performance evaluation using $R^2$ Score, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

---

## 📊 Strategic Recommendations for Management
* **Inventory & Supply Chain:** Anticipate the massive Q4 seasonal surge by scaling logistics ahead of time.
* **Targeted Marketing:** Focus paid advertising campaigns on peak international markets and optimal high-conversion time slots identified through temporal heatmaps.

---
