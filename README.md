# 📊 Sales Analysis Dashboard

## 📌 Project Overview

The **Sales Analysis Dashboard** is an interactive Power BI project created to analyze sales performance, profitability, customers, products, and regional trends.

The dashboard helps transform raw sales data into meaningful business insights using **Power BI, DAX, and data visualization**.

---

## 🎯 Project Objectives

* Analyze overall sales and profit performance
* Track sales and profit trends over time
* Identify top-performing products and categories
* Analyze sales performance across different regions, states, and cities
* Understand customer purchasing patterns
* Analyze the impact of discounts on sales and profit
* Create an interactive dashboard for business decision-making

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard creation and data visualization
* **DAX** – Calculated measures and business calculations
* **Microsoft Excel / CSV** – Dataset
* **Power Query** – Data cleaning and transformation

---

## 📂 Dataset

The dataset contains **3,000 sales records** with the following columns:

| Column       | Description                    |
| ------------ | ------------------------------ |
| OrderID      | Unique order identification    |
| OrderDate    | Date of the order              |
| CustomerID   | Unique customer identification |
| CustomerName | Customer name                  |
| Product      | Product purchased              |
| Category     | Product category               |
| Quantity     | Quantity sold                  |
| UnitPrice    | Price per unit                 |
| Discount     | Discount percentage            |
| Sales        | Total sales amount             |
| Cost         | Product cost                   |
| Profit       | Profit generated               |
| Region       | Sales region                   |
| State        | Customer state                 |
| City         | Customer city                  |

---

## 📈 Dashboard KPIs

The dashboard focuses on important business KPIs such as:

* 💰 **Total Sales**
* 📈 **Total Profit**
* 📦 **Total Quantity Sold**
* 👥 **Total Customers**
* 🛒 **Total Orders**
* 📊 **Profit Margin**
* 💵 **Average Order Value**

---

## 📊 Dashboard Analysis

### 1. Sales Performance

* Total sales and order performance
* Sales trends over time
* Monthly and yearly sales analysis

### 2. Profit Analysis

* Total profit generated
* Profit margin analysis
* Comparison between sales and profit

### 3. Product Analysis

* Best-selling products
* Product-wise sales
* Product-wise profit
* Category performance

### 4. Regional Analysis

* Sales by region
* State-wise performance
* City-wise sales analysis

### 5. Customer Analysis

* Customer-wise sales
* Customer purchasing behavior
* Top customers based on sales

### 6. Discount Analysis

* Discount impact on sales
* Discount impact on profit
* Comparison of discounted and non-discounted sales

---

## 🧮 DAX Measures

Some important DAX calculations used in the project include:

```DAX
Total Sales = SUM(Sales_Data[Sales])
```

```DAX
Total Profit = SUM(Sales_Data[Profit])
```

```DAX
Total Quantity = SUM(Sales_Data[Quantity])
```

```DAX
Total Orders = DISTINCTCOUNT(Sales_Data[OrderID])
```

```DAX
Total Customers = DISTINCTCOUNT(Sales_Data[CustomerID])
```

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

---

## 📊 Power BI Visualizations

The dashboard uses different visualizations to make the analysis easy to understand:

* KPI Cards
* Line Charts
* Bar Charts
* Column Charts
* Donut Charts
* Tables
* Slicers
* Maps / Geographic visuals

---

## 🔍 Key Insights

The dashboard can be used to identify:

* Which products generate the highest sales
* Which products generate the highest profit
* Which categories perform best
* Which regions and states contribute the most revenue
* Which customers generate the highest sales
* How sales change over time
* How discounts affect profitability

---

## 📁 Project Files

```text
Sales_Analysis_DashBoard/
│
├── Sales_DashBoard.pbix
├── Sales_Data.csv
└── README.md
```

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Sales_DashBoard.pbix` using **Microsoft Power BI Desktop**.
3. Explore the dashboard using the available filters and slicers.
4. Use the dataset to understand the calculations and analysis.

---

## 💡 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Analysis
* Power BI Dashboard Development
* DAX
* Data Visualization
* KPI Creation
* Business Intelligence
* Sales & Profit Analysis

---
