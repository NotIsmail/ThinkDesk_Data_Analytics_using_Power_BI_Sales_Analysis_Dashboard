# Retail Sales Performance Dashboard (Power BI)


# Project Overview

This project is a Sales Analysis Dashboard built using Microsoft Power BI to analyze the sales performance of a retail company. The dashboard helps management understand sales trends, regional performance, product performance, and salesperson performance using interactive visualizations and KPI indicators.

This project was created as part of a Power BI Dashboard Assignment.

## Project Statement

The objective of this project is to design an interactive dashboard to analyze retail sales data and answer key business questions. The dashboard must include KPI indicators, multiple visualizations, slicers for filtering, and a clean layout to support data-driven decision-making.

Dataset Fields Used
Date
Product
Category
Region
Salesperson
Customer Segment
Quantity
Sales Amount
Profit
Target
Dashboard Features

## The dashboard includes the following components:

KPI Indicators
Total Sales
Total Profit
Total Quantity Sold
Total Target
Profit Margin
Sales vs Target
Visualizations
Line Chart – Sales Trend Over Time
Column Chart – Sales by Region
Bar Chart – Top Selling Products
Pie Chart – Sales by Category
Column Chart – Sales by Salesperson
Scatter Plot – Sales vs Profit
Map – Geographical Sales Distribution
Slicers (Filters)
Date
Region
Category
Customer Segment

These slicers allow interactive filtering of the dashboard.


## The following measures were created in Power BI:

Total Sales = SUM(sales_data[SalesAmount])
Total Profit = SUM(sales_data[Profit])
Total Quantity = SUM(sales_data[Quantity])
Total Target = SUM(sales_data[Target])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Sales vs Target = [Total Sales] - [Total Target]
Dashboard Layout

The dashboard is organized into the following sections:

KPI cards at the top
Sales trend analysis
Regional and product performance
Category contribution
Sales vs Profit relationship
Salesperson performance
Geographical sales distribution
Interactive slicers for filtering


## Insights from Dashboard

The dashboard shows overall company performance through KPIs.
Sales trend helps identify growth patterns over time.
Certain regions generate higher sales compared to others.
Laptops/Phones (top products) contribute the highest revenue.
Electronics category contributes the largest share of sales.
There is a positive relationship between sales and profit.
Some salespersons perform significantly better than others.
Sales vs Target KPI shows whether the company met its target.

## Files in This Repository

sales_data.csv → Dataset used
Sales_Dashboard.pbix → Power BI dashboard file
README.md → Project documentation
Project_Statement.pdf → Assignment description
