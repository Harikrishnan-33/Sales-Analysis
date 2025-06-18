# 📊 Sales Analysis Dashboard using Power BI

Welcome to the **Sales Analysis Dashboard** project! This project provides deep insights into retail sales data through interactive visualizations, helping businesses make informed decisions.

---

## 🧠 Project Objective

To analyze historical sales data and create a comprehensive Power BI dashboard that showcases key sales metrics, customer insights, product performance, and geographic trends.

---

## 📁 Dataset Overview

- **Rows:** 2,823  
- **Columns:** 25 (18 used after cleaning)  
- **Key Columns:**
  - `ORDERDATE`, `SALES`, `QUANTITYORDERED`
  - `PRODUCTLINE`, `CUSTOMERNAME`, `COUNTRY`
  - `DEALSIZE`, `STATUS`

---

## 🧹 Data Cleaning

Performed in **Jupyter Notebook** using **Python (Pandas)**:
- Removed irrelevant columns (`ORDERLINENUMBER`, `CONTACTLASTNAME`)
- Dropped `STATE` column due to many missing values
- Converted `ORDERDATE` to `datetime`
- Handled missing data in `ADDRESSLINE2`, `TERRITORY`
- Saved cleaned dataset to `cleaned_sales_data.csv`

---

## 🛠️ Tools Used

| Tool           | Purpose                        |
|----------------|--------------------------------|
| **Python**     | Data cleaning and preprocessing|
| **Jupyter Notebook** | Coding environment         |
| **Pandas**     | Data manipulation              |
| **Power BI**   | Dashboard and visualization    |

---

## 📊 Power BI Dashboard Features

### ✅ KPIs:
- Total Sales
- Total Orders
- Average Order Value
- Total Quantity Ordered

### 📈 Visualizations:
- Monthly Sales Trend (Line Chart)
- Sales by Country (Bar Chart)
- Deal Size Distribution (Pie Chart)
- Product Line Performance (Column Chart)
- Top 10 Customers (Bar Chart)

### 🎛 Filters (Slicers):
- Year  
- Country  
- Product Line  
- Deal Size  

---

## 💡 Insights Discovered

- **USA** is the highest revenue-generating country.
- **Classic Cars** is the most popular product line.
- **Medium** deal sizes dominate overall sales.
- Sales show seasonal trends, especially in Q2 and Q4.
- A few top customers contribute significantly to total revenue.

---


## 👤 Author

**Harikrishnan V**  
📧 harikrishnanv134@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/harikrishnanv134)

