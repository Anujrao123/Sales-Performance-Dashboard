# Sales-Performance-Dashboard
## 📌 Project Overview
This Sales Performance Dashboard is created using Power BI to analyze
overall sales performance, profit trends, and product-wise contribution.
It helps business users understand performance quickly and make
data-driven decisions.

## 🎯 Business Objectives
- Track total sales and profit
- Monitor sales trends over time
- Identify top-performing products
- Analyze category-wise performance

## 📈 Key KPIs
- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin %

## 📊 Dashboard Visuals
- KPI Cards – Sales, Profit, Orders
- Line Chart – Sales Trend (Monthly)
- Bar Chart – Top Products
- Donut Chart – Category-wise Sales
- Table – Sales Details

## 🛠️ Tools & Skills Used
- Power BI
- DAX (Measures and Calculations)
- Data Modeling
- Data Cleaning

## 🧮 Sample DAX Measures
```DAX
Total Sales = SUM(Sales[Sales Amount])
Total Profit = SUM(Sales[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

