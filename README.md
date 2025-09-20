# cafe-sales-dashboard
Power BI Dashboard with data cleaning in Python analyzing café sales, product performance, and customer trends.

Project Overview

This project is a Power BI dashboard analyzing sales data for a café. It provides insights on overall sales, product performance, and customer/location trends to help make data-driven decisions.

Key Features:

Interactive dashboards with multiple pages

Cross-page slicers and filters

Cleaned and processed data for accurate analysis

Dataset

Raw Data: raw_data.csv – Uncleaned CSV file with transaction records

Cleaned Data: cleaned_data.csv – Data after preprocessing in Python (Jupyter Notebook / VS Code)

Data Cleaning Steps (Python):

Checked and corrected data types (dates, numeric fields).

Handled missing values (filled with 0 or appropriate values).

Standardized column names (lowercase, no spaces).

Saved cleaned dataset as cleaned_data.csv for Power BI.

Power BI Report

File: dashboard.pbix

The report consists of three pages:

Page 1 – Sales Overview

KPIs / Cards:

Total Sales (Sum of total_sales)

Total Transactions (Count of transaction_id)

Average Sales per Transaction (Total Sales ÷ Transactions)

Average Quantity per Transaction

Charts:

Line Chart → Sales over time (transaction_date vs total_sales)

Clustered Column Chart → Sales by month

Page 2 – Product Performance

Charts:

Bar Chart → Total Sales by Item (Top products)

Column Chart → Quantity Sold by Item

Pie/Donut Chart → Revenue share by Item

Table:

Top 10 items with columns: item, total quantity, total sales

Page 3 – Customer & Location Analysis

Charts:

Pie/Donut Chart → Sales by Payment Method

Stacked Column Chart → Sales by Location (In-store vs Takeaway)

Line/Bar Combo → Sales trend by Location over time

Project Screenshots

Screenshots of the dashboard pages are in the screenshots/ folder:

sales_overview.png

product_performance.png

customer_location_analysis.png
