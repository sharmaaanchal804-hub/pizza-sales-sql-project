# 🍕 Pizza Sales SQL Analysis Project

## 📌 Overview
This project analyzes pizza sales data using SQL.  
The goal is to extract meaningful insights such as top-selling pizzas, revenue analysis, order trends, and customer behavior patterns.

The project uses **MySQL** and includes several analytical SQL queries such as joins, aggregations, window functions, and groupings.

---

## 📁 Database Tables Used
The database contains the following tables:

- **orders** → stores order information (order_id, order_date, order_time)
- **order_details** → stores details of each pizza in an order
- **pizzas** → contains pizza size, price, and IDs
- **pizza_types** → contains pizza names and categories

---

## 🧠 Key SQL Concepts Used
- JOINs (INNER JOIN)
- GROUP BY & ORDER BY
- Aggregate functions: `SUM()`, `COUNT()`, `AVG()`
- Window function: `SUM() OVER()`
- Subqueries
- Date & Time functions (`HOUR()`)
- Aliasing
- LIMIT

---

## 📊 Analysis Performed

### ✔ 1. Total number of orders  
Counts all orders placed.

### ✔ 2. Total revenue from pizza sales  
Calculates revenue using `quantity × price`.

### ✔ 3. Highest priced pizza  
Identifies the costliest pizza on the menu.

### ✔ 4. Most common pizza size  
Finds which pizza size is ordered most often.

### ✔ 5. Top 5 most ordered pizza types  
Based on quantities sold.

### ✔ 6. Category-wise pizza quantity  
Shows which category (Classic, Supreme, etc.) sells the most.

### ✔ 7. Orders by hour  
Distribution of orders throughout the day.

### ✔ 8. Category-wise pizza distribution  
Counts pizzas in each category.

### ✔ 9. Average pizzas ordered per day  
Shows overall daily order frequency.

### ✔ 10. Top 3 pizzas by revenue  
Identifies the highest earning pizzas.

### ✔ 11. Revenue percentage by category  
Contribution of each pizza category to total revenue.

### ✔ 12. Cumulative revenue over time  
Uses a window function to calculate running revenue.

---

## 📂 Project Files
- **pizza_sales_project.sql** → Contains all SQL queries used in the analysis  
- **README.md** → Project documentation  
- **screenshots folder** (optional)

---

## 🚀 How to Run This Project
1. Create a database in MySQL:
   ```sql
   CREATE DATABASE pizza_hut;

