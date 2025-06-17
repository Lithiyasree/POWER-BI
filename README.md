# POWER-BI
PIZZA SALES REPORT DASHBOARD

# 🍕 Pizza Sales Dashboard | Power BI Project

## 📌 Project Overview

This project focuses on building a **Pizza Sales Dashboard** using **Power BI**. It involves importing raw sales data, creating a relational database using **SQL Server**, writing complex queries, cleaning and processing the data, and finally visualizing it through interactive reports.

The goal is to generate actionable business insights from the pizza sales dataset by analyzing key performance indicators (KPIs) and visualizing sales trends using various chart types.

---

## 🛠️ Software & Tools Used

- **Microsoft Excel / Office** – Data formatting and initial cleaning
- **SQL Server 2019** – Database creation and data manipulation
- **SQL Server Management Studio (SSMS 21)** – Querying and management
- **Power BI Desktop** – Data visualization and dashboard creation

---

## ⚙️ Project Workflow

### 1. Importing Data

- Raw pizza sales data imported from `.csv` files (e.g., orders, pizzas, order_details, pizza_types)
- Source files cleaned and formatted in Excel before importing into SQL Server

### 2. Creating the Database

- Created `PizzaSales` database in SQL Server
- Created and normalized tables:
  - `orders`
  - `order_details`
  - `pizzas`
  - `pizza_types`

### 3. Writing Queries

SQL queries written to:
- Join tables and calculate KPIs
- Aggregate data (daily/monthly trends)
- Derive insights for visualizations

### 4. Connecting to Power BI

- Connected Power BI to SQL Server
- Imported cleaned and processed tables
- Created calculated columns and measures in Power BI

### 5. Data Cleaning & Processing

- Removed null values
- Standardized date/time formats
- Applied DAX to create new measures like `Total Revenue`, `Average Order Value`, etc.

---

## 📈 KPIs Tracked

1. **Total Revenue** – Sum of total price of all pizza orders  
2. **Average Order Value** – Total revenue ÷ total number of orders  
3. **Total Pizzas Sold** – Sum of quantities of all pizzas sold  
4. **Total Orders** – Total number of orders placed  
5. **Average Pizzas per Order** – Total pizzas sold ÷ total orders

---

## 📊 Charts & Visualizations

| Visualization | Description |
|---------------|-------------|
| 📅 **Daily Trend of Orders** | Bar chart showing day-wise total orders |
| 🕒 **Hourly Trend of Orders** | Line chart showing order trends by hour |
| 🍕 **Sales % by Pizza Category** | Donut chart showing share by category |
| 🍕 **Sales % by Pizza Size** | Pie chart showing share by size |
| 📉 **Pizzas Sold by Category** | Funnel chart for quantity sold by category |
| 🏆 **Top 5 Pizzas** | Bar charts for top 5 by revenue, quantity, and orders |
| 🚫 **Bottom 5 Pizzas** | Bar charts for bottom 5 by revenue, quantity, and orders |

---

## 🔍 Problem Statement

To gain actionable insights from the pizza sales data, focusing on key metrics such as revenue, order patterns, category preferences, and top/bottom performers.

This helps in:

- Identifying best-selling products
- Understanding customer preferences
- Planning marketing strategies and inventory

---

## 📌 Conclusion

This project demonstrates how data can be transformed into valuable insights using a combination of SQL and Power BI.
