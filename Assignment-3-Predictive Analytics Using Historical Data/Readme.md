# Assignment 3 – Predictive Analytics Using Historical Data

## 📌 Overview

This project is part of my **Thiranex Internship – Assignment 3**.

The objective of this assignment is to build a predictive analytics model using historical sales data to identify trends and forecast future sales. The project covers data cleaning, exploratory data analysis, trend analysis, regression modeling, model evaluation, and future sales forecasting.

The analysis is implemented using **Python and Jupyter Notebook** with libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn.

---

## 🎯 Objectives

* Clean and preprocess historical sales data
* Analyze historical sales trends
* Perform exploratory data analysis
* Build regression models for sales prediction
* Compare model performance using evaluation metrics
* Visualize actual and predicted sales
* Forecast future sales trends

---

## 📂 Dataset

The dataset contains sales-related information including:

* Product Name
* ID
* Sales
* Quantity
* Price
* City
* Customer
* Date

The dataset contains **1,500 records and 8 columns** with no missing values or duplicate rows in the analyzed data.

### Data Period

* **Start Date:** April 1, 2018
* **End Date:** March 31, 2019
* **Unique Dates:** 307

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning models and evaluation

---

## 🔍 Project Workflow

### 1. Data Loading

The historical sales dataset is loaded using Pandas and initially inspected to understand its structure, columns, and data types.

### 2. Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked dataset shape and column information
* Checked missing values
* Checked duplicate records
* Converted the `Date` column into datetime format
* Removed duplicate rows

The dataset remained at **1,500 records after duplicate removal**.

### 3. Exploratory Data Analysis

Key sales statistics were analyzed, including:

* Total Sales
* Total Quantity
* Average Price
* Sales by Product
* Sales trends over time

The analyzed dataset has total sales of **431,502** and total quantity of **5,615**.

### 4. Trend Analysis

Sales data was aggregated over time to understand historical sales patterns and visualize the overall trend.

### 5. Predictive Modeling

Two regression models were implemented:

#### Linear Regression

Linear Regression was used to model the relationship between time and sales and generate sales predictions.

#### Random Forest Regression

Random Forest Regression was also trained and evaluated to compare its predictive performance with Linear Regression.

### 6. Model Evaluation

The models were evaluated using:

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score**

#### Model Performance

| Model             |       MAE |      RMSE | R² Score |
| ----------------- | --------: | --------: | -------: |
| Linear Regression | 13,630.23 | 15,886.61 |  -1.3742 |
| Random Forest     | 14,319.02 | 17,337.32 |  -1.8276 |

Based on the notebook's evaluation results, **Linear Regression performed better than Random Forest on this test set**, with lower MAE and RMSE and a higher R² score.

### 7. Future Sales Forecasting

The project generates a future sales forecast and visualizes the forecasted values alongside historical sales.

The final visualization presents:

* Historical Sales
* Forecasted Sales
* Future dates
* Overall sales trend

The notebook specifically plots the historical sales together with future forecasted sales.

---

## 📊 Visualizations

The notebook includes visualizations for:

* Historical sales trends
* Product-wise sales
* Actual vs Predicted Sales
* Historical Sales vs Future Forecast

These visualizations help understand historical patterns and communicate the model's predictions.

---

## 📈 Key Learnings

Through this project, I gained practical experience in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Time-based trend analysis
* Regression modeling
* Comparing machine learning models
* Model evaluation using MAE, RMSE, and R²
* Sales forecasting
* Data visualization
* Using historical data for predictive analytics

---

## 📁 Project Structure

```text
Assignment-3/
│
├── Sales_Forecasting_Predictive_Analytics.ipynb
├── combined_product_sales_predictive_data.csv
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository.

2. Navigate to the Assignment 3 folder.

3. Make sure the dataset file is present in the same directory as the notebook.

4. Open the Jupyter Notebook:

```bash
jupyter notebook Sales_Forecasting_Predictive_Analytics.ipynb
```

5. Run the notebook cells sequentially.

---

## 🏢 Internship

**Internship Program:** Thiranex Internship
**Assignment:** 3
**Topic:** Predictive Analytics Using Historical Data

---

## 👨‍💻 Author

**Aditya Khanna**

---

⭐ If you found this project useful, feel free to explore the other assignments in this repository.

