# 🧾 Supermarket Sales Power BI Dashboard

## 📊 Overview
An interactive Power BI dashboard designed to analyze supermarket sales performance, profitability, and customer behavior across branches, product lines, and time.

---

## 🎯 Key Features
- KPI Cards: Total Sales, Profit Margin, Avg Transaction Value
- Visuals: Sales trends, product performance, customer insights
- Filters: City, Branch, Product Line, Customer Type, Date, Payment
- Time-Series and Heatmap Analysis
- Clean UI with custom color theme

---

## 🧮 DAX Measures
```DAX
Average Transaction Value = 
DIVIDE(SUM('supermarket_sales'[Total]), DISTINCTCOUNT('supermarket_sales'[Invoice ID]))

Profit Margin (%) = 
DIVIDE(SUM('supermarket_sales'[gross income]), SUM('supermarket_sales'[cogs])) * 100

🎨 Theme
Background: #F5F3EF (Warm Beige)

📂 Files
• Supermarket_Sales.csv– Excel file
• README.md – Project overview
• sales.png - power bi dashboard
• Supermarket_Sales_Summary.ppt - Summary

This project is licensed under the MIT License.
