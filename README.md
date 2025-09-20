# cafe-sales-dashboard
Power BI Dashboard with data cleaning in Python analyzing café sales, product performance, and customer trends.

## Project Overview

This project demonstrates an end-to-end data analytics workflow using Python and Power BI. Python (Jupyter Notebook) was used for data cleaning, and Power BI was used to visualize café sales, product performance, and customer trends.

## Dataset

-raw_data.csv – Original, uncleaned dataset
-cleaned_data.csv – Cleaned and prepared for analysis

Key Columns: transaction date, product name, quantity, total sales, payment method

## Data Cleaning:  
**performed in python**
- Removed duplicates
- Standardized column names
- Converted data types
- Handled missing values (filled with 0)
- Converted transaction dates to datetime

## Power BI Report

- **Page 1** – Sales Overview: Total sales, average sales, transactions, trends over time
- **Page 2** – Product Performance: Top-selling products, revenue share
- **Page 3** – Customer & Location Analysis: Payment methods, in-store vs takeaway comparison

## Key Insights

- Salad and Juice are the top-selling items
- Card payments are more popular than cash
- Instore orders are increasing

## Conclusion

This project highlights how Python and Power BI can be combined to analyze and visualize sales data for actionable business insights.
