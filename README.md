# Pharmaceutical-Retail-Sales-Analysis-Dashboard

## 📌 Project Overview
This project is a **Power BI Dashboard** that analyzes pharmaceutical retail sales over a 4-year period.  
It provides insights into sales performance by product class, customer type, region, sales representatives, and overall sales trends.  

The dashboard is interactive, automatically refreshed daily, and designed to help decision-makers make data-driven business strategies.

---

## 📊 Key Features
- **KPI Cards:** Total Sales
- **Sales Trends:** Monthly and yearly turnover analysis.
- **Product Class Performance:** Identify top revenue-generating product classes.
- **Customer Segmentation:** Pharmacy vs Hospital sales contribution.
- **Geographic Insights:** Sales by country using a map visual.
- **Sales Team Performance:** Sales contribution by individual reps.
- **Scatter Plot Analysis:** Quantity sold vs total sales to detect pricing/volume patterns.
- **Interactive Filters (Slicers):** Year, Month, Country, Sales Team.

---

## 🛠️ Tech Stack
- **Tool:** Power BI Desktop & Power BI Service
- **Language:** DAX (Data Analysis Expressions)
- **Data Prep:** Power Query Editor
- **Data Source:** Pharma Retail Dataset (CSV)

---

## 🧮 DAX Measures Used
- **Total Sales:**
```DAX
Total Sales = SUM('pharma-data'[Sales])

