# 🍕 Pizza Sales Analysis using SQL

## 📌 Project Overview

This project analyzes pizza sales data using SQL to uncover insights related to revenue, customer behavior, and product performance.

The goal is to solve real-world business questions using structured query techniques such as joins, aggregations, and window functions.

---

## 🎯 Objective

* Measure total sales performance
* Identify top-selling pizzas and categories
* Understand ordering patterns
* Analyze revenue trends over time

---

## 🛠️ Tools Used

* MySQL
* SQL (Joins, Aggregations, Subqueries, Window Functions)

---

## 📂 Dataset Description

The dataset consists of four relational tables:

* **orders**
  Contains order-level details such as **order_id, order_date, and order_time**, used to analyze ordering patterns over time.

* **order_details**
  Stores transaction-level data including **order_id, pizza_id, and quantity**, representing the number of pizzas in each order.

* **pizzas**
  Includes information about pizzas such as **pizza_id, size, and price**, used for revenue analysis.

* **pizza_types**
  Contains details like **pizza_type_id, name, and category**, helping classify pizzas into different categories.


---

## 📁 Project Structure

```id="7v1j7s"
pizza-sales-sql/
│
├── dataset/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   ├── pizza_types.csv
│
├── sql/
│   ├── basic_queries.sql
│   ├── intermediate_queries.sql
│   ├── advanced_queries.sql
│
├── presentation/
│   └── pizza_sales_analysis.pdf
│
├── screenshots/
│   ├── total_orders.png
│   ├── revenue.png
│   ├── top_pizzas.png
│
└── README.md
```

---

## 🔍 Key Analysis

### 🟢 Basic

* Total number of orders
* Total revenue
* Highest-priced pizza
* Most common size
* Top 5 pizzas

### 🟡 Intermediate

* Category-wise quantity
* Orders by hour
* Average pizzas per day
* Top pizzas by revenue

### 🔴 Advanced

* Revenue contribution (%)
* Cumulative revenue trend
* Top pizzas by category

---

## 📸 Sample Outputs

### Total Orders

![Total Orders](screenshots/total_orders.png)

### Revenue Calculation

![Revenue](screenshots/revenue.png)

### Top 5 Pizzas

![Top Pizzas](screenshots/top_pizzas.png)

---

## 📈 Key Insights

* A few pizza types contribute a large share of revenue
* Peak ordering occurs during specific hours of the day
* Larger pizza sizes are more frequently ordered
* Revenue shows a cumulative growth trend over time

---

## ⚠️ Disclaimer

This project is for learning and portfolio purposes only.
The dataset is publicly available and does not represent real business data.

---

## 👨‍💻 Author

**Dixit**

---
