# 📊 Product Sales Performance Analysis & Smart Recommendations

This Power BI project delivers actionable insights from a product-based company’s sales dataset. 
The goal is to help stakeholders identify trends, evaluate performance,
and make data-driven decisions using interactive visuals, KPIs, and smart filters.

> ✅ Tools Used: **SQL** · **Python** · **Power BI**  
> 📁 Pages: 2 (Executive Overview & Product Insights)  
> 📌 Key Focus: Sales Performance · Product Line Trends · Deal Sizes · Profit Margins · Customer Insights

---

## 📁 Project Overview

- **SQL**: Used for initial data cleaning (date formats, nulls), filtering, grouping, and EDA.
- **Python**: Used for EDA, feature engineering, and ML preparation (not visualized in dashboard).
- **Power BI**: Designed a 2-page interactive dashboard with slicers, KPIs, and visual insights.

---

## 🖼️ Dashboard Snapshots

### 🔹 Page 1: Executive Sales Overview

![Executive Sales Overview](product%20sales%20dashboard-1.jpg)

**Visuals Included**:
- ✅ KPI Cards: Total Sales, Total Orders, Total Customers
- 📊 Deal Size %: Large, Medium, Small
- 📈 Total Sales by Month (Line Chart)
- 🌍 Sales by Country (Map Chart)
- 📦 Sales by Product Line (Bar Chart)
- 🧩 Total Sales by Deal Size (Donut Chart)
- 🏆 Top 10 Customers by Sales (Bar Chart)
- 🎛️ Slicers: `Year`, `Deal Size`, `Product Line`
- 🧭 Navigation Buttons: **Home**, **Insights**

---

### 🔹 Page 2: Product Sales Insights

![Product Sales Insight](product%20sales%20dashboard-2.jpg)

**Visuals Included**:
- 📦 Sales by Product Line (%) (100% Stacked Bar)
- 💰 Average Order Value by Product Line (₹ format)
- 🏆 Top 10 Products by Quantity Ordered
- 🌍 Top 5 States by Sales
- 🧩 Sales by Product Line (Donut Chart with %)
- 📉 Profit Margin by Product Line (Horizontal Bar)
- 🎛️ Slicers: `Year`, `Deal Size`, `Product Line`
- 🧭 Navigation Buttons: **Home**, **Insights**

---

## 📌 Key Insights

- **Top Product Line**:  
  `Classic Cars` is the leader with ₹3.9M in sales (39% market share).

- **Deal Size Split**:  
  - Medium Deals: **61%**  
  - Small Deals: **26%**  
  - Large Deals: **13%**

- **Customer Behavior**:  
  Top customers include `Euro Shoppe`, `Mini Gift Store`.

- **Profit Margins**:  
  All product lines show **negative margins**, with `Trains` being lowest (-39%).

- **Geographic Trends**:  
  Most sales are from **North America** and **Europe**, with `California` being top state.

---

## 📊 DAX Measures Created

- ✅ **Large/Medium/Small Deal %**
- ✅ **Average Order Value (by ProductLine)**
- ✅ **Profit Margin %**
- ✅ **Top N Customers/Products by Sales**
- ✅ **KPI Cards with formatting**

---

## 🔧 How to Use This Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Use the **slicers** to filter by Year, Product Line, and Deal Size.
3. Switch between **Home** and **Insights** using the buttons.
4. Export filtered views as PDF/image for reports or presentations.

---

## 📁 Summary

| Feature            | Description                                      |
|--------------------|--------------------------------------------------|
| Tools Used         | SQL, Python, Power BI                            |
| Pages              | 2 (Overview & Insights)                          |
| Key Visuals        | Bar, Donut, Line, Map, KPI Cards                 |
| Filters Applied    | Product Line, Year, Deal Size                    |
| Output             | Business-ready dashboard for sales performance   |

---

## 🙌 Credits

**Created by**: [Bipin Kumar]  
**Dataset**: Real-world structured sales data  
**Dashboard Tool**: Power BI

---

