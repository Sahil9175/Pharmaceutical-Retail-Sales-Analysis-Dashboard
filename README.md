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

## Business Insights
Pharmacies contribute the majority of sales (~60%).
Certain product classes drive most revenue → should receive higher investment.
Top-performing countries generate significantly higher sales → expansion opportunities.
Seasonal patterns observed in monthly sales → better inventory & campaign planning.
Few sales reps drive majority of sales → need to train underperformers.

## How to Use
Download the .pbix file from this repository.
Open it in Power BI Desktop.
Explore interactive visuals, slicers, and filters.
For automatic refresh → publish to Power BI Service and configure scheduled refresh.


## Author
Sahil Rajendra Palshetkar.
Data Analyst | Power BI Enthusiast
📧 Email: sahilpalshetkar8822@gmail.com
🌐 LinkedIn: www.linkedin.com/in/sahil-palshetkar-473744280
