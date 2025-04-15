# 📊 Global Superstore Dashboard – Power BI (Medallion Architecture)

🚀 This project showcases an end-to-end Business Intelligence dashboard built using **Power BI**, structured around the **Medallion Architecture** approach in **Microsoft Fabric**. The dashboard provides dynamic, insightful analytics based on the popular **Global Superstore dataset**.

---

## 🧱 Medallion Architecture Breakdown

### 🥉 Bronze Layer – Raw Data Ingestion  
- Loaded the original `.xlsx` file: `global_superstore_data.xlsx`
- Explored and verified columns like `Order Date`, `Sales`, `Region`, `Product Category`, etc.
- Checked for nulls, duplicates, and inconsistent formatting

### 🥈 Silver Layer – Data Cleaning & Transformation  
- Cleaned country, category, and date fields
- Removed nulls and outliers from `Sales` and `Profit` columns
- Converted date columns into proper date types
- Created calculated columns (e.g., `Year`, `Month`, `Profit Margin`)

### 🥇 Gold Layer – Semantic Model & Business View  
- Modeled key relationships between `Orders`, `Customers`, `Products`, and `Regions`
- Built a star schema for optimized querying in Power BI
- Defined key measures using **DAX**:
  - Total Sales
  - Total Profit
  - Avg. Discount
  - Profit Margin
  - YoY Growth (optional metric)

---

## 📊 Dashboard Highlights

- 📌 **KPI Cards**: Quick view of Sales, Profit, Discounts
- 📈 **Trend Analysis**: Sales & Profit over time with filters
- 🌎 **Region Breakdown**: Performance by Country and Segment
- 📦 **Product-Level Insights**: Category-wise profit & shipping status
- 🎯 **Filters**: Interactive slicers by Region, Category, Sub-Category, Segment, etc.

---

## 🔗 Live Demo

👉 [**View Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZDY1ZDc3YzctZmE5MC00ZGUyLTkzY2ItNjk1MDIyNWEzMTQ1IiwidCI6IjQxOGRkOGU3LTgwYzAtNGQwOC1iOTg5LTI4ZTVhODU4YzY4ZiJ9)

---

## 🛠️ Tools & Tech Used

- Power BI
- Excel
- DAX
- Microsoft Fabric (Conceptual Medallion Architecture)
- Data Cleaning & Modeling

---

## 📁 Dataset

The original dataset is provided in this repo:  
📂 `global_superstore_data.xlsx`

---

## 📌 Key Learnings

- Applied Medallion Architecture mindset to traditional BI project
- Enhanced performance and clarity by organizing data into layers
- Used DAX for dynamic and reusable business metrics
- Practiced stakeholder-centric dashboard design
