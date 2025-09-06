# 🪑 Furniture Sales Analysis Dashboard

This project presents an **interactive Excel dashboard** for analyzing sales performance of **Furniture shop** across different regions, states, and product categories.  

The dashboard provides a **comprehensive view of business KPIs**, helping stakeholders track revenue, cost, profit, and customer trends over time.  

---

![Capture](https://github.com/user-attachments/assets/f29f0a57-033a-4565-8bbc-9916a10be89d)

---
<img width="613" height="448" alt="Screenshot 2025-09-06 095616" src="https://github.com/user-attachments/assets/d1e8bda4-b75f-497d-bc00-a7648cd50b13" />

---

## 📑 Table of Contents
- [Project Overview](#-furniture-sales-analysis-dashboard)
- [📊 Key Features](#-key-features)
- [💡 Business Insights](#-business-insights)
- [🛠 Tools Used](#-tools-used)
- [🧹 Data Cleaning](#-data-cleaning)
- [🏗 Data Modeling](#-data-modeling)
- [🎯Business Questions](#-business-questions)



## 📊 Key Features
- **Total Sales, Cost, Profit & Gross Margin** tracking.
- **Customer & Order insights**: unique orders, transaction averages, and quantities sold.
- **Top 5 States & Cities by Sales** for geographical performance analysis.
- **Top 10 Products by Sales** with category contribution.
- **Sales by Region** (West, South, Midwest, Northeast).
- **Time trend analysis** (Quarterly sales performance).
- **Interactive filters** by **Year** and **Region** for dynamic analysis.

---

## 💡 Business Insights
- **Highest Sales Region:** West region led in total sales.  
- **Top Performing State:** California generated the largest revenue.  
- **Customer Insights:** 50 unique customers contributed to overall sales.  
- **Best-Selling Products:** Accessories and Rugs dominated product sales.  
- **Profitability:** Net profit margin achieved ~29%.  

---

## 🛠 Tools Used
- **Microsoft Excel**: PivotTables, Power Query, and PivotCharts.  
- **Data Visualization**: Line charts, bar charts, pie charts, and KPI cards.  
- **Dashboard Interactivity**: Slicers for region and year filtering.

---

## 🧹 Data Cleaning
Performed in **Power Query Editor**:
- Removed duplicates and blank rows  
- Standardized column names  
- Handled missing data (imputation/removal where necessary)  
- Changed data types for consistency (dates, currency, integers)  
- Renamed and reordered columns for clarity  
- Created calculated columns (e.g., `SalesValue = OrderQuantity * UnitPrice`)
  
<img width="1366" height="728" alt="Data Cleaning" src="https://github.com/user-attachments/assets/d74076e4-e202-4304-add4-5a2b4dc51a09" />

---

## 🏗 Data Modeling
Designed a **Star Schema** in Power Pivot with relationships between fact and dimension tables:

- **Fact Table**: `Fact_Transactions` (Order Quantity, Unit Cost, Sales Value, etc.)  
- **Dimension Tables**: Customers, Products, Regions, Sales Persons, Store Locations, and Dates  
- Built **primary–foreign key relationships** to enable robust analysis  

✅ This model supports drill-down reporting by time, region, product, and customer.

![Data Modeling](https://github.com/user-attachments/assets/9540b43e-6a88-4173-8649-41454f131e6c)


---

## 🎯 Business Questions
This dashboard helps management quickly answer key questions:  
- Which regions and states generate the most revenue?  
- What are the top-performing products driving sales?  
- How are sales trends evolving across years and quarters?  
- What is the profitability margin across the business?  

---

📌 With this analysis, business leaders can make **data-driven decisions** about product focus, regional strategy, and customer engagement.  
