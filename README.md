# Cognevance Level 2 – Sales Forecasting System

## Project Overview

This project was completed as part of the Cognevance Internship – Level 2 (Intermediate).

The objective of this project is to analyze historical sales data and build a simple forecasting model to predict future sales.

I used Python and its data analysis and machine learning libraries to clean the data, analyze sales trends, build a Linear Regression forecasting model, and visualize the results.

## Project Objectives

- Collect and prepare historical sales data
- Clean and preprocess the dataset
- Analyze monthly and yearly sales trends
- Build a sales forecasting model
- Predict future sales for 2025
- Compare actual sales with predicted sales
- Generate business insights and recommendations

## Dataset

The dataset contains daily sales records from 2019 to 2024.

It includes the following columns:

- Date
- Sales
- Orders
- Quantity
- Profit
- Year
- Month
- Month_Name

The dataset contains 2,192 records.

**Note:** The dataset used in this project is simulated/sample data created for learning and internship purposes. It does not represent real company sales data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

### 1. Data Loading

The sales dataset was loaded into Python using Pandas.

### 2. Data Cleaning

I checked the dataset for:

- Missing values
- Duplicate records
- Incorrect data types

The Date column was converted into the proper datetime format.

### 3. Sales Trend Analysis

I analyzed:

- Total sales
- Average daily sales
- Yearly sales
- Monthly sales
- Highest and lowest sales periods

### 4. Forecasting Model

A Linear Regression model was used to forecast future monthly sales.

The historical monthly data was divided into:

- Training data – 60 months
- Testing data – 12 months

### 5. Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 6. 2025 Sales Forecast

The trained model was used to forecast monthly sales for 2025.

## Key Results

- Total historical sales: 3,017,779.63
- Average daily sales: 1,376.72
- Best sales year: 2024
- Lowest sales year: 2019
- Best sales month: December
- Lowest sales month: January
- Forecasted 2025 sales: 672,867.93
- Forecasted growth compared with 2024: 7.81%

### Model Performance

- MAE: 2850.05
- RMSE: 3254.00
- R² Score: -0.0078

The negative R² score shows that the simple Linear Regression model does not explain the month-to-month sales variation very well. However, the project demonstrates the complete forecasting workflow from data preparation to prediction and business interpretation.

## Business Insights

From the analysis, I observed that:

- Sales generally increased over the years.
- December had the highest total monthly sales.
- January had the lowest total monthly sales.
- The forecast indicates an overall increase in sales for 2025.
- The forecast can help with basic planning for inventory and resources.

## Business Recommendations

- Prepare sufficient inventory for high-sales months.
- Consider promotional campaigns during lower-sales periods.
- Compare actual sales with forecasted sales regularly.
- Future models can include additional factors such as discounts, prices, products, holidays, and customer information.

## Project Files

The repository contains:

- `sales_forecasting.ipynb` – Complete Python/Google Colab notebook
- `Cognevance_Level2_Sales_Forecasting_Dataset.csv` – Sales dataset
- `sales_forecast_2025.csv` – 2025 forecast results
- `sales_forecasting_linear_regression_model.pkl` – Trained Linear Regression model
- `historical_vs_forecast_2025.png` – Historical vs forecast visualization
- `Cognevance_Level2_Sales_Forecasting_Humanized_Report.docx` – Project report

## Conclusion

This project helped me understand the basic workflow of a sales forecasting system. I worked with historical sales data, performed data cleaning and trend analysis, built a Linear Regression forecasting model, evaluated the model, and generated predictions for 2025.

The project also helped me understand how forecasting can be used to support business planning and decision-making.

## Internship

**Cognevance Internship – Level 2**

**Project:** Sales Forecasting System

**Student:** LIKHITH CHEMUDURI

**Domain:** Data Analytics
