# 🛒 Superstore Sales & Profit Analysis

## 📌 Project Overview

This project analyzes retail sales data from a Superstore dataset to uncover business insights and understand the key factors affecting profit. It also includes a basic machine learning model to predict profit based on available features.

The goal is to simulate a real-world business scenario where data is used to support decision-making.

---

## 🎯 Objectives

* Analyze sales and profit trends across regions and categories
* Identify key drivers that impact profit
* Perform data cleaning and feature engineering
* Build and evaluate machine learning models for profit prediction

---

## 📊 Dataset Information

The dataset contains transactional sales data with the following key features:

* Sales
* Profit
* Quantity
* Discount
* Category / Sub-Category
* Region

⚠️ Note: The dataset does not include cost price, which limits the accuracy of profit prediction.

---

## 🧹 Data Preprocessing

* Handled missing and inconsistent values
* Converted categorical variables using one-hot encoding
* Removed infinite values and replaced them with safe defaults
* Prepared clean dataset for modeling

---

## ⚙️ Feature Engineering

Created additional features to improve model understanding:

* **Avg_Sales_per_Quantity** = Sales / Quantity
* **Discount_Value** = Discount × Sales

These features help capture business logic like pricing efficiency and discount impact.

---

## 📈 Exploratory Data Analysis (EDA)

Key analysis performed:

* Sales and profit distribution
* Regional performance comparison
* Category-wise profit trends
* Impact of discount on profit

---

## 🤖 Machine Learning

### Models Used:

* Linear Regression
* Random Forest Regressor

### Evaluation Metrics:

* Mean Absolute Error (MAE)
* R² Score

### Results:

* Model performance was limited (low R² score)
* Random Forest performed slightly better than Linear Regression

---

## 📌 Key Insights

* Sales is the strongest factor influencing profit
* High discounts often reduce profitability
* Certain regions consistently perform better
* Feature engineering slightly improved model performance

---

## ⚠️ Limitations

* No cost/procurement data → limits profit prediction accuracy
* Dataset is not rich enough for high-performing ML models
* Model is more suitable for learning than production use

---

## 🚀 Future Improvements

* Add cost data or external features
* Try advanced models (XGBoost, LightGBM)
* Perform hyperparameter tuning
* Build a dashboard using Power BI / Streamlit

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## 📂 Project Structure

* `Superstore_sales_profit_analysis.ipynb` → Full analysis and ML model
* `README.md` → Project documentation

---

## 💡 Conclusion

This project demonstrates the end-to-end workflow of a data science problem:
data cleaning → analysis → feature engineering → modeling → evaluation.

While the model performance is limited, the project highlights strong fundamentals and practical understanding of data analysis.

---

## 👨‍💻 Author

Raviraj Chopade
