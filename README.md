# Pizza Sales SQL Analytics

## 📌 Project Overview
This project analyzes pizza sales data using SQL to uncover key business insights.  
It includes queries for:
- **Average Daily Orders** – Calculates the average number of pizzas sold per day.
- **Top 3 Pizzas by Revenue** – Identifies the best-selling pizza types based on total revenue.
- **Cumulative Revenue Over Time** – Tracks sales growth using SQL window functions.

## 🗂 Dataset
- **order_details.csv** – Contains pizza order quantities and IDs.
- **orders** – Order date and ID details.
- **pizzas** – Pizza price and type identifiers.
- **pizza_types** – Names and categories of pizzas.

## 🛠 Technologies Used
- **SQL** (PostgreSQL/MySQL compatible syntax)
- **Joins, Aggregations, Window Functions**

## 📊 Key Queries
1. **Average pizzas ordered per day** – Uses `AVG()` and subqueries.  
2. **Top 3 pizzas by revenue** – Combines joins and `GROUP BY` with `ORDER BY LIMIT`.  
3. **Cumulative revenue analysis** – Implements `SUM() OVER()` for running totals.

## 🚀 How to Run
1. Import dataset into your SQL database.
2. Run each `.sql` file:
   - `10.sql` → Average daily orders.
   - `11.sql` → Top pizzas by revenue.
   - `13.sql` → Cumulative revenue analysis.
3. View results for business decision-making.

## 📈 Sample Insights
- The business can identify high-performing products.
- Track sales growth trends for better forecasting.
- Understand average daily demand for inventory planning.

---
**Author:** Akash Chaudhary  
**License:** MIT
