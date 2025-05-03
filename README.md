# 📊 Power BI Project – Sales Performance Dashboard

## 📁 Dataset
**Filename:** `Power BI Project - Sales Performance Dashboard.xlsx`

This Excel file contains transactional sales data used to build an interactive Power BI dashboard. It includes key fields like Order ID, Product Category, Sales Amount, Profit, Region, and Order Date.

---

## 🎯 Objective
The goal of this project was to design a dynamic and business-friendly dashboard that enables sales teams and decision-makers to:
- Analyze total sales, profit, and orders over time
- Monitor KPIs like growth, margin, achievement %, and target benchmarks
- Understand category-wise and region-wise performance
- Use filters and drill-throughs for deeper exploration

---

## 💡 Features & Highlights
- **Interactive KPIs**: Total Sales, Total Profit, Total Orders, Profit Margin, Sales Growth %
- **DAX-Powered Metrics**:
  - Year-over-Year (YoY) and Month-over-Month (MoM) calculations
  - Dynamic Sales Growth % and Achievement %
  - Discount Impact across categories
  - Recency measure for behavioral insights
- **Visual Insights**:
  - Sales by Year (trend line)
  - Profit by Category (bar chart)
  - Region-Wise Profit vs Sales (100% stacked bar)
  - Daily Sales Trends (line chart)
  - Map View by Country (geographic distribution)
  - Gauge Chart for Sales vs Target
- **Dynamic Slicers and Filters** for Region, Category, Time Period, etc.

---

## 📐 DAX Measures Explained
- **Total Sales**: Sum of all transaction sales (main KPI)
- **Total Profit**: Sum of profit (Sales - Cost)
- **Total Orders**: Count of distinct transactions
- **Profit Margin**: `(Total Profit / Total Sales) * 100`
- **Sales Growth %**: `(Sales - Previous Year Sales) / Previous Year Sales * 100`
- **Sales Growth**: Sales difference compared to previous year
- **Sales by Year**: Aggregated annual sales
- **Previous Year Sales**: Lookup for past year value used in YoY calcs
- **Sales Achievement %**: `(Total Sales / Target Sales) * 100`
- **Target Sales**: Static/forecast value used in goal analysis
- **Discount Impact**: Derived metric showing how discounts impact profits
- **Recency**: Days since last transaction (for customer engagement)
- **Measure**: Placeholder or testing formula used during development

---

## 📌 Strategic Insights
This dashboard bridges the gap between raw data and executive decision-making by offering:
- Instant visibility into performance KPIs
- Business alignment via target benchmarks and achievements
- Actionable insights into underperforming categories or regions
- Enhanced storytelling using visual, filterable, and temporal dimensions

It’s ideal for:
- Business leaders to review trends
- Sales teams to identify top-performing products and gaps
- Data teams to validate goals and customer behavior

---

## 📷 Screenshots
> Include visuals such as:
> - KPI dashboard (Total Sales, Profit, Growth %)
> - Region-wise bar chart
> - Category-wise profit
> - Target vs Actual (gauge)
> - Geo map view

---

## 🛠️ Tools Used
- **Power BI Desktop**
- **Microsoft Excel** (data source)
- **DAX** for all calculated columns and measures

---

## 📂 Folder Structure
```
📁 Power-BI-Sales-Dashboard/
├── 📄 Power BI Project - Sales Performance Dashboard.xlsx
├── 📄 Power_BI_Sales_Dashboard.pbix
├── 📄 README.md

```

---

## 📬 Contact
If you have any questions or would like to collaborate, feel free to connect with me on [LinkedIn](#) or check out my [portfolio website](#).
