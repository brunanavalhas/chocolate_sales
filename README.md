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
