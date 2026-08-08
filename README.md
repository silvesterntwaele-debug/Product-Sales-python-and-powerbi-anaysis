# Product-Sales-python-and-powerbi-anaysis
End-to-end sales &amp; product analytics project — data cleaning, EDA, correlation, regression, and a Power BI dashboard built on South African retail data.

# Sales & Product Performance Analysis

An end-to-end data analytics project exploring sales and product data for a South African retail dataset — from raw CSVs to a fully interactive Power BI dashboard.

## Overview
This project analyzes sales transactions and product catalog data to uncover revenue trends, profitability by category and supplier, and pricing dynamics. It combines Python for data cleaning and statistical modeling with Power BI for interactive visualization.

## Datasets
- `sales.csv` — 1,217 transaction records (Quantity, UnitPrice, Discount, LineTotal)
- `products.csv` — 31 products with cost, price, category, and supplier info
- Merged on `ProductID` to create a unified analytical dataset

## Process
1. **Data Cleaning** — validated data types, checked for duplicates/nulls, verified calculated fields
2. **Feature Engineering** — created Revenue, TotalCost, Profit, and Margin columns
3. **Exploratory Data Analysis** — category/supplier breakdowns, top products by revenue and quantity
4. **Correlation Analysis** — examined relationships between price, cost, discount, and profitability
5. **Regression & Prediction** — built a linear regression model to predict LineTotal from Quantity, UnitPrice, and UnitCost (R² ≈ 0.85)
6. **Power BI Dashboard** — interactive visuals including KPI cards, profit-by-category charts, top-10 product rankings, and a profit margin gauge against a 30% target

## Tools
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Power BI (Power Query, DAX)

## Key Insights
- [Add 2–3 bullet points of your actual findings here, e.g. "Electronics category had the highest average margin at X%"]

## Dashboard Preview
[Add a screenshot of your final Power BI dashboard here]
