# Adidas Sales & Profitability Insights Dashboard

## Project Overview

This project analyzes Adidas sales data to uncover insights related to **revenue, profitability, product performance, and regional trends**.

The goal is to move beyond basic reporting and identify **key business drivers** that can help optimize pricing, product mix, and regional strategy.

---

## 🎯 Business Objective

* Identify **high-performing products and regions**
* Analyze **profitability vs sales volume**
* Detect **underperforming segments**
* Provide **data-driven recommendations** for business optimization

---

## 📁 Dataset Information

* Source: Excel dataset
* Records: ~9,600 rows
* Fields: 13 columns
* Key Columns:

  * Total Sales
  * Operating Profit
  * Units Sold
  * Price per Unit
  * Region, State, Product, Retailer

---

## 🧠 Key KPIs Created

* **Total Revenue**
* **Total Operating Profit**
* **Total Units Sold**
* **Average Price per Unit**
* **Profit per Unit**
* **Profit Margin % (Weighted)**

---

## 📊 Dashboard Features

### 🟢 Executive Summary

* KPI cards for quick performance overview
* Sales trend over time
* Geographic sales distribution

### 🔵 Product Performance Analysis

* Scatter plot showing **Volume vs Profitability**
* Identification of:

  * High-volume, low-margin products
  * High-margin, low-volume opportunities

### 🟣 Regional & Retail Insights

* Sales by region and state
* Top-performing retailers
* Regional performance comparison

---

## 💡 Key Insights

* A small group of products contributes significantly to overall revenue
* Some high-volume products generate lower margins, indicating pricing optimization opportunities
* Regional performance is uneven, suggesting targeted expansion strategies
* Certain retailers dominate sales, highlighting strong distribution partnerships

---

## 🛠 Tools & Technologies

* **Power BI**
* Power Query (Data Cleaning & Transformation)
* DAX (Data Analysis Expressions)

---

## ⚙️ Key DAX Measures

```DAX
Total Profit = SUM('Data Sales Adidas'[Operating Profit])

Total Units = SUM('Data Sales Adidas'[Units Sold])

Profit per Unit = DIVIDE([Total Profit], [Total Units])

Profit Margin % = DIVIDE(
    SUM('Data Sales Adidas'[Operating Profit]),
    SUM('Data Sales Adidas'[Total Sales])
)
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use filters (Region, Date) to explore insights
4. Interact with visuals for deeper analysis

---

## 📌 Project Highlights

* Focus on **business problem-solving**, not just visualization
* Use of **advanced visuals (scatter plot)**
* Implementation of **dynamic KPIs using DAX**
* Clean and structured dashboard design

---

## 📈 Future Improvements

* Add forecasting for sales trends
* Include customer segmentation
* Enhance data model with multiple tables
* Add drill-through and tooltips for deeper insights

---

## 👤 Author

**Mahesh Rajpurohit**
Aspiring Data Analyst | Business Analyst

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub and connect with me!
