# 📊 Retail Sales & Profitability Analysis Dashboard

### Executive Business Intelligence Report using Power BI
---
<img width="1397" height="796" alt="dashboard-preview" src="https://github.com/user-attachments/assets/d6533142-6841-4667-a9a7-f130e0a4ab22" />

---

## 🔎 Business Problem

Retail businesses require structured visibility into revenue growth, profitability drivers, and product-level contribution to make strategic pricing and inventory decisions.

Without centralized reporting, management struggles to:

* Monitor monthly sales trends
* Identify high-margin product categories
* Detect low-performing sub-categories
* Understand profit distribution across products

This project delivers an executive-level dashboard to support data-driven decision-making.

---

## 🎯 Project Objective

To design an interactive Power BI dashboard that:

* Tracks overall retail performance
* Analyzes category and sub-category profitability
* Identifies top-performing products
* Highlights margin optimization opportunities
* Enables quick executive-level insights

---

## 📂 Dataset

**Source:** Superstore Retail Dataset

**Key Fields:**

* Order ID
* Order Date
* Category & Sub-Category
* Sales
* Profit
* Quantity

The dataset was cleaned, transformed, and modeled within Power BI prior to visualization.

---

## 📈 Key Performance Indicators (KPIs)

| KPI               | Description                      |
| ----------------- | -------------------------------- |
| Total Sales       | Overall revenue generated        |
| Total Profit      | Net profitability                |
| Profit Margin (%) | Efficiency of revenue conversion |
| Total Orders      | Business activity volume         |

---

## 📊 Dashboard Components

### 1️⃣ Executive Summary

Top KPI cards providing an immediate snapshot of financial health.

### 2️⃣ Monthly Sales Trend Analysis

Time-series visualization (2014–2017) to detect:

* Growth patterns
* Seasonal peaks
* Revenue momentum

### 3️⃣ Category-Level Profitability

Revenue vs profit comparison across:

* Technology
* Furniture
* Office Supplies

### 4️⃣ Sub-Category Analysis

Highlights:

* High-revenue, low-margin segments
* Performance imbalance
* Optimization opportunities

### 5️⃣ Top Profitable Products

Ranks products contributing most significantly to total profit.

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

* Technology category drives the highest profitability.
* Furniture shows strong revenue but comparatively lower margins.
* Profit contribution is concentrated among a limited number of products.
* Sales demonstrate steady year-over-year growth with seasonal spikes.

---

## 📌 Business Recommendations

Based on analysis:

* **Improve margin strategy in Furniture category** through pricing optimization or cost control.
* **Expand high-margin Technology products** via targeted marketing.
* Focus on **top-performing SKUs** for inventory prioritization.
* Investigate low-margin sub-categories for operational inefficiencies.

---

## 🚀 Business Impact

This dashboard enables stakeholders to:

* Monitor financial performance effectively
* Detect underperforming segments early
* Improve pricing and inventory strategies
* Support executive-level reporting

---

## 🔮 Future Enhancements

* Year-over-Year (YoY) growth comparison
* Forecasting using Power BI analytics tools
* Dynamic Top-N product selector
* Drill-through product detail page
* Profitability heatmap visualization

---

## 🛠 Tools & Technologies

* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Cleaning & Transformation
* Business Intelligence Reporting

---

## 📎 How to Use

1. Download the `.pbit` template file from this repository.
2. Open in Microsoft Power BI Desktop.
3. Load the Superstore dataset when prompted.
4. Explore interactive filters and visual insights.

---

## 📌 Project Category

Business Intelligence | Retail Analytics | Data Visualization | Power BI

---

