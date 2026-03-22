# Chocolate Sales Dashboard

## Project Overview
This project analyzes chocolate sales data using **Python** for data cleaning and preparation, and **Power BI** for data visualization.

The goal was to explore sales performance across different countries, products, and sales representatives, and to build an interactive dashboard that highlights key business insights.

## Tools Used
- **Python**
  - pandas
- **Power BI**
- **GitHub**

## Dataset
The dataset used in this project contains chocolate sales records, including:
- Sales person
- Country
- Product
- Date
- Amount
- Boxes shipped

## Data Cleaning and Preparation
The dataset was cleaned and transformed in Python before being imported into Power BI.

Main cleaning steps:
- Renamed columns for easier use in Python
- Converted `amount` to numeric format
- Converted `date` to datetime format
- Removed duplicates
- Removed missing or invalid values
- Created new columns for analysis:
  - `year`
  - `month`
  - `month_name`
  - `year_month`
  - `amount_per_box`

## Dashboard Features
The Power BI dashboard includes:
- **Total Revenue**
- **Total Boxes Shipped**
- **Total Orders**
- **Average Revenue per Box**
- **Monthly Revenue Trend**
- **Revenue by Country**
- **Top Products by Revenue**
- **Top Sales People by Revenue**

It also includes interactive filters to explore the data by country, product, sales person, and date.

## Key Insights
Some of the main business questions explored in this project:
- Which countries generate the highest revenue?
- Which products perform best?
- Which sales people generate the most sales?
- How do sales change over time?

## Project Structure
```text
chocolate-sales-dashboard/
│
├── data/
│   ├── Chocolate Sales.csv
│   └── chocolate_sales_clean.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── dashboard/
│   └── chocolate_sales_dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.mdg<img width="732" height="1397" alt="image" src="https://github.com/user-attachments/assets/4582633c-4000-4636-83d6-e38f9bf81f96" />
