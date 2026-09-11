# Walmart Sales Prediction & Time-Series Forecasting

## 📌 Project Overview

This project implements an end-to-end Machine Learning pipeline using the Walmart Sales Dataset.

The objective is to analyze historical sales data, identify important patterns and factors affecting sales, build regression models for weekly sales prediction, optimize the best model using hyperparameter tuning, and forecast future monthly sales.

## 🎯 Objectives

- Perform data preprocessing and cleaning
- Conduct Exploratory Data Analysis (EDA)
- Perform feature engineering using date information
- Build regression models for sales prediction
- Compare Linear Regression and Random Forest Regression
- Perform hyperparameter tuning using RandomizedSearchCV
- Evaluate models using MAE, RMSE and R²
- Perform time-series analysis
- Forecast future monthly sales
- Generate actionable business insights

## 📊 Dataset

The project uses the Walmart Sales Dataset containing historical weekly sales information.

### Main Features

- `Store` - Store identification number
- `Date` - Weekly sales date
- `Weekly_Sales` - Weekly sales amount
- `Holiday_Flag` - Indicates whether the week is a holiday week
- `Temperature` - Temperature during the week
- `Fuel_Price` - Fuel price
- `CPI` - Consumer Price Index
- `Unemployment` - Unemployment rate

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🤖 Machine Learning Models

### Regression Models

1. Linear Regression
2. Random Forest Regression
3. Tuned Random Forest Regression

### Hyperparameter Tuning

RandomizedSearchCV was used to optimize the Random Forest model by testing different combinations of:

- Number of estimators
- Maximum depth
- Minimum samples split
- Minimum samples leaf
- Maximum features

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Lower MAE and RMSE indicate better performance, while a higher R² score indicates better explanatory power.

## ⏳ Time-Series Forecasting

Historical weekly sales were aggregated into monthly sales.

A moving-average forecasting approach was then implemented to:

- Evaluate forecasting performance on the test period
- Forecast the next 6 months of sales
- Visualize historical and future sales trends

## 💡 Business Insights

The analysis can help businesses with:

- Sales forecasting
- Inventory planning
- Promotional planning
- Resource allocation
- Store-level performance analysis
- Understanding seasonal sales patterns

## 📁 Repository Structure

```text
Walmart-Sales-ML-Forecasting/
│
├── Assignment_2_Walmart_Sales_ML.ipynb
├── Walmart_Sales.csv
└── README.md
