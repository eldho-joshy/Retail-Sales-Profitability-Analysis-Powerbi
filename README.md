# 📊 Retail Sales & Profitability Analysis Dashboard

### Executive Business Intelligence Report using Power BI
<img width="1397" height="796" alt="dashboard-preview" src="https://github.com/user-attachments/assets/d6533142-6841-4667-a9a7-f130e0a4ab22" />

---

## 🔎 Business Problem

Retail management requires clear, structured visibility into sales trends, product performance, and profitability drivers to support strategic decision-making.

Without centralized reporting, it becomes difficult to:

* Monitor revenue growth over time
* Identify high-margin product categories
* Detect low-performing sub-categories
* Understand profit contribution by product

This project addresses that challenge by developing an executive-level Power BI dashboard for retail performance monitoring.

---

## 🎯 Project Objective

To design an interactive and insight-driven dashboard that:

* Tracks overall sales and profit performance
* Analyzes category and sub-category profitability
* Identifies top-performing products
* Visualizes monthly revenue trends
* Enables data-driven business decisions

---

## 📂 Dataset

**Dataset Used:** Superstore Retail Dataset

**Data Fields Include:**

* Order ID
* Order Date
* Product Category & Sub-Category
* Sales
* Profit
* Quantity

The dataset was cleaned, transformed, and modeled inside Power BI before visualization.

---

## 📈 Key Performance Indicators (KPIs)

| KPI               | Purpose                              |
| ----------------- | ------------------------------------ |
| Total Sales       | Measures overall revenue performance |
| Total Profit      | Tracks business profitability        |
| Profit Margin (%) | Evaluates operational efficiency     |
| Total Orders      | Indicates business activity volume   |

---

## 📊 Dashboard Components

### 1️⃣ Executive KPI Summary

Top-level KPI cards providing an immediate snapshot of business health.

### 2️⃣ Monthly Sales Trend Analysis

Time-series visualization (2014–2017) to identify:

* Growth trends
* Seasonal patterns
* Revenue momentum

### 3️⃣ Category-Level Performance

Comparison of major product categories:

* Technology
* Furniture
* Office Supplies

Highlights revenue vs profit contribution.

### 4️⃣ Sub-Category Analysis

Identifies:

* High-revenue, low-margin segments
* Optimization opportunities

### 5️⃣ Top Profitable Products

Ranks products contributing most to overall profitability.

---

## 🧮 DAX Measures Implemented

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

Total Orders =
DISTINCTCOUNT(Superstore[Order ID])
```

---

## 💡 Key Business Insights

* Technology category drives the highest overall profit.
* Furniture generates strong revenue but comparatively lower margins.
* Profit contribution is concentrated among a limited number of high-performing products.
* Sales show consistent growth with identifiable seasonal peaks.

---

## 🛠 Tools & Technologies

* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Cleaning & Transformation
* Business Intelligence Reporting

---

## 🚀 Business Value

This dashboard enables stakeholders to:

* Monitor financial performance in real-time
* Optimize pricing and margin strategies
* Focus marketing efforts on high-profit products
* Detect underperforming categories early

---

## 📌 Project Type

Business Intelligence | Data Visualization | Retail Analytics

---

