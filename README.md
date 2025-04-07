# 🧱 Microsoft Fabric Data Engineering Project — Tricathon (Bronze → Gold)

This project demonstrates an **end-to-end Data Engineering pipeline** using **Microsoft Fabric**, structured using the **Medallion Architecture** pattern: Bronze, Silver, and Gold layers.

---

## 🧩 Technologies Used

- ✅ Microsoft Fabric (Lakehouse, Notebooks)
- ✅ PySpark
- ✅ Pandas
- ✅ Power BI (optional for Gold layer)
- ✅ OneLake storage

---

## 📁 Project Overview

| Layer  | Description |
|--------|-------------|
| 🟤 Bronze | Raw CSV data ingested from Lakehouse: Customers, Sales, Product, Category, Calendar, Territories |
| ⚪ Silver | Data cleaned and transformed using PySpark (sorting, null filters, casting) |
| 🟡 Gold  | Final datasets ready for Power BI reporting or analytics |

---

## 🛠️ Steps Performed

- Read multiple raw datasets from Lakehouse storage using `spark.read`
- Applied cleaning via PySpark (`.sort`, `.dropna`, etc.) and some Pandas
- Saved structured data back to Lakehouse paths in Silver layer
- (Optional) Aggregated or joined data for business logic in Gold layer

---

## 📸 Screenshots
Linkage Architecture 
![image](https://github.com/user-attachments/assets/bc36ee2b-7346-4b21-80e7-e3fc3dbd32c5)


## 🔗 Live Demo (Optional)

[📊 Power BI Public Link (if published)](https://app.powerbi.com/...)

---

## 🧠 Concepts Demonstrated

- Delta Lake tables and versioned storage
- Medallion Architecture in Microsoft Fabric
- Notebooks in PySpark for transformation
- Multi-source data integration and cleansing

---

## 📂 Repo Structure

