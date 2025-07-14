# 📊 Product Sales Performance Analysis & Smart Recommendations

This Power BI project delivers deep insights from a product-based company’s sales data to help decision-makers monitor performance, 
discover trends, and drive actionable strategies.

> ✅ Tools Used: **SQL** · **Python** · **Power BI**  
> 📁 Pages: 2 (Executive Overview & Product Insights)  
> 🎯 Goal: Clean, analyze, and visualize product sales data with smart filters and business KPIs.

---

## 📁 Project Overview

| Phase     | Tools Used | Description |
|-----------|------------|-------------|
| 🔹 **Data Cleaning**  | SQL        | Cleaned raw data: converted `ORDERDATE` from text to date, removed nulls, 
                         corrected data types, performed filtering/grouping to prepare for analysis. |
| 🔹 **Data Analysis + ML** | Python     | Performed EDA, feature engineering, and built a **Random Forest model** for 
                             **sales forecasting**. Final forecast output was not deployed on dashboard (modeling-only). |
| 🔹 **Visualization** | Power BI   | Designed a professional 2-page interactive dashboard to display executive KPIs and deep product insights using DAX & slicers. |

---

## 🖼️ Dashboard Snapshots

### 🔹 Page 1: Executive Sales Overview

![Executive Sales Overview](product%20sales%20dashboard-1.jpg)

**Visuals Included**:
- ✅ KPI Cards: `Total Sales`, `Total Orders`, `Total Customers`
- 📊 Deal Size %: `Large`, `Medium`, `Small` Deals
- 📈 Total Sales by Month (Line Chart)
- 🌍 Sales by Country (Map Chart)
- 📦 Sales by Product Line (Bar Chart)
- 🧩 Total Sales by Deal Size (Donut Chart)
- 🏆 Top 10 Customers by Sales
- 🎛️ Slicers: `Year`, `Deal Size`, `Product Line`
- 🧭 Navigation Buttons: **Home**, **Insights**

---

### 🔹 Page 2: Product Sales Insights

![Product Sales Insight](product%20sales%20dashboard-2.jpg)

**Visuals Included**:
- 📦 Sales by Product Line with % (100% Stacked Bar)
- 💰 Average Order Value by Product Line
- 📦 Top 10 Products by Quantity Ordered
- 🗺️ Top 5 States by Sales
- 🧩 Sales by Product Line (Donut Chart with %)
- 📉 Profit Margin by Product Line
- 🎛️ Slicers: `Year`, `Deal Size`, `Product Line`
- 🧭 Navigation Buttons: **Home**, **Insights**

---

## 📌 Key Insights

- **Top Product Line**:  
  `Classic Cars` generated ₹3.9M (39% of total sales).

- **Customer Segments by Deal Size**:  
  - Medium Deals: **61%**
  - Small Deals: **26%**
  - Large Deals: **13%**

- **Customer Loyalty**:  
  `Euro Shoppe` and `Mini Gift Store` contributed the highest sales volume.

- **Profitability Insights**:  
  All products have **negative profit margins**, with `Trains` lowest at **-39%**.

- **Regional Trends**:  
  Majority sales are from **North America** and **Europe**, with top state: **California (CA)**.

---

## 📊 DAX Measures Used

- ✅ `Average Order Value` by Product Line
- ✅ `Profit Margin %` calculation
- ✅ Deal size % breakdown
- ✅ Top N filtering (Top 10 customers/products)
- ✅ Conditional formatting in KPI cards

---

## 🧠 Machine Learning Work (Python)

- Built a **Random Forest model** to forecast future sales using historical order data.
- Focused on training, testing, and optimizing model performance.
- ❗Note: Forecast output **not shown** in Power BI (for modeling purposes only).

---

## 🔧 How to Use This Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Filter data using slicers: `Year`, `Product Line`, and `Deal Size`.
3. Navigate between **Home** and **Insights** pages via buttons.
4. Use visuals for quick KPIs, trends, and product-level decisions.

---

## 📁 Summary Table

| Feature            | Description                                      |
|--------------------|--------------------------------------------------|
| Tools Used         | SQL, Python, Power BI                            |
| Pages              | 2 (Executive Overview & Product Insights)        |
| DAX Measures       | 5+ (Deal %, AOV, Margin, Top N, KPIs)            |
| Python ML          | Random Forest Model for Sales Forecasting        |
| SQL Work           | Full data cleaning and transformation            |
| Key Visual Types   | Bar, Donut, KPI, Line, Map, 100% stacked         |
| Filters Applied    | Product Line, Year, Deal Size                    |

---

## 🙌 Credits

**Created by**: [Bipin Kumar]  
**Dataset**: Real-world structured product sales data  
**Dashboard Tool**: Power BI  
**ML Library**: `scikit-learn` (Python)

---









