# Sales Performance Analytics & Demand Prediction Pipeline

## Overview
This project demonstrates an end-to-end data analytics and machine learning pipeline using real-world retail sales data.
The workflow includes data storage in PostgreSQL, analysis using SQL and Python, exploratory data analysis, and a baseline machine learning model for sales prediction.

## Tech Stack
- PostgreSQL
- Python
- Pandas, NumPy
- Matplotlib
- scikit-learn
- SQLAlchemy, psycopg2

## Dataset
Retail sales dataset containing order, customer, product, and sales information.

## Project Workflow
1. Loaded raw sales data into PostgreSQL.
2. Queried and extracted data into Python using SQLAlchemy.
3. Cleaned and preprocessed data using Pandas.
4. Performed exploratory data analysis to identify trends and key revenue drivers.
5. Built a baseline Linear Regression model to predict sales.
6. Improved model performance using feature engineering and categorical encoding.

## Key Insights
- Sales peaked in 2018, indicating strong year-over-year growth.
- Technology is the highest revenue-generating category.
- High-value sub-categories (e.g., copiers) contribute disproportionately to total sales.
- Adding product-level features significantly improved model performance.

## Machine Learning Results
- Baseline model (time features only): R² ≈ 0
- Improved model (category + sub-category): R² ≈ 0.16
- RMSE reduced from ~595 to ~543 through feature engineering.

## Conclusion
This project highlights the importance of combining SQL, data analysis, and machine learning to build scalable and explainable analytics pipelines.
The focus was on understanding data behavior and feature importance rather than maximizing predictive accuracy.
