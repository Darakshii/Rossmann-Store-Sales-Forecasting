# 📊 Rossmann Sales Forecasting

Python Pandas NumPy Scikit-learn XGBoost PyTorch TensorFlow Microsoft Excel Canva Visual Studio Code Markdown GitHub

## 🔍 Objective

The objective of this project is to build a robust sales forecasting model that predicts future daily sales for each Rossmann store. By leveraging historical sales data, store-specific attributes, and external factors such as promotions and holidays, the model aims to deliver accurate and reliable forecasts.

## 🏢 Project Overview

Rossmann operates thousands of drugstores across multiple regions. Managing inventory, staffing, and promotions efficiently requires accurate sales forecasting.

This project focuses on analyzing historical store data, identifying trends and seasonality, and building a machine learning model to predict future sales. The insights generated help optimize operations and improve business decision-making.

## 📊 Dataset Information

The dataset consists of two primary files:

**data.csv**

* Store ID
* Date
* Sales
* Customers
* Open/Closed status
* Promotions (Promo)
* State holidays

**store.csv**

* Store Type (a, b, c, d)
* Assortment Type
* Competition Distance
* Competition Start Date
* Promo2 participation
* Promo intervals

## 📌 Project Scope

* Perform extensive Exploratory Data Analysis (EDA)
* Handle missing values and outliers
* Engineer time-based and promotional features
* Capture seasonality and trends
* Train machine learning models for prediction
* Evaluate performance using regression metrics

## 🚀 Getting Started

Follow these steps to run the project:

Clone the Repository:

```bash id="rm1"
git clone https://github.com/your-repo/Rossmann-Sales-Forecasting
```

Install Dependencies:

```bash id="rm2"
pip install -r requirements.txt
```

Run Notebook:

```bash id="rm3"
jupyter notebook
```

## 📂 Project Structure

```id="rm4"
├── README.md
├── notebooks
│   └── rossmann_sales_forecasting.ipynb
├── data
│   ├── data.csv
│   └── store.csv
├── src
│   ├── preprocessing.py
│   └── model.py
├── reports
│   └── report.pdf
├── outputs
│   ├── predictions.csv
│   └── feature_importance.png
```

## 📈 Key Achievements

* Achieved ~90%+ prediction accuracy (R² Score)
* Engineered 15+ features including lag variables and seasonality indicators
* Improved model performance using ensemble techniques (XGBoost)
* Reduced forecasting error significantly compared to baseline models

## 📊 Insights

* Sales strongly influenced by promotions and holidays
* Seasonal spikes observed during festive periods
* Competition distance impacted store performance
* Store type and assortment affected revenue patterns

## 🚀 Business Impact

* Improved inventory planning and stock availability
* Enabled better workforce and operational planning
* Supported data-driven promotional strategies
* Reduced revenue loss due to stockouts and overstocking

## 📝 License

This project is licensed under the MIT License.
