# 🚀 Scalable Retail Branch Analytics Using PySpark

---

## 🎯 Business Objective

Retail companies with multiple branches generate millions of transactions. Managers need to:

- Track sales performance across regions and branches
- Identify top-performing products and employees
- Plan inventory, marketing, and staffing based on trends

This project builds a complete **PySpark-based analytics pipeline** to solve that — from data cleaning to KPI reporting and visualization.

---

## 🧠 What You’ll Learn

- How to work with **large-scale structured data** in PySpark
- Write **efficient ETL pipelines** using DataFrames and Spark SQL
- Compute **intermediate and advanced KPIs**
- Use **Window functions, aggregations, joins**, and filtering
- Export outputs for **BI dashboards** (Power BI, Tableau, etc.)

---

## 🧾 Dataset Description

This is a synthetic dataset created to resemble real-world company transaction logs.

| Column         | Description                      |
|----------------|----------------------------------|
| Branch_ID      | Store location code              |
| Date           | Transaction date                 |
| Product_Code   | Internal SKU                     |
| Units_Sold     | Quantity sold                    |
| Revenue        | Revenue in ₹                     |
| Region         | North, South, East, West         |
| Sales_Rep      | Salesperson who completed sale   |

📁 **File**: `retail_branch_data.csv` (100,000 rows)

---

## 📊 KPIs Calculated

### ✅ Intermediate KPIs

1. Total Revenue per Region  
2. Total Revenue per Branch  
3. Monthly Revenue Trend  
4. Average Revenue per Transaction  
5. Units Sold per Product  
6. Average Units Sold per Branch  
7. Revenue per Sales Rep  
8. Number of Transactions per Day  
9. Daily Revenue  


---

### 🚀 Advanced KPIs

1. Top 5 Branches by Revenue (Window Function)  
2. Top 5 Sales Reps by Avg Revenue per Transaction  
3. Peak Sales Day (per Region)  
4. Average Basket Size (Units/Transaction)  
5. Revenue Variance across Regions  
6. Monthly Revenue Growth Trend  
7. Product Performance Index  
8. Simulated Churn Indicator  
9. Regional Revenue Share %  


---

## 📈 Visualization Output

Although PySpark doesn’t support plotting natively, selected KPIs were exported to Pandas and visualized using Matplotlib:

- 📅 Monthly Revenue Trends  
- 🏬 Top Branches by Revenue  
- 👨‍💼 Top Sales Reps

---

## 🛠️ Tools & Technologies

- Apache Spark (PySpark)
- Google Colab / Jupyter Notebook
- Pandas (for export/plot)
- Matplotlib
- Faker (for data generation)

---

## 📣 Usage

1. Clone this repo  
2. Open `Pyspark_Project.ipynb`  
3. Run the PySpark cells (requires Spark)  
4. Use outputs for your own Power BI/Tableau dashboards!

---

## ✅ Ideal For:

- Final year students & interns
- Data Analyst/Engineer portfolio
- GitHub showcase for product teams
- ML Engineers with Spark exposure

