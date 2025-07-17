# 🍽️ Restaurant (SQL Project)

This SQL project simulates a restaurant database and provides insights into menu items, order trends, and customer behavior. It is designed to showcase data analysis skills using SQL on relational data.

---

## 📁 Project Structure

| File / Folder | Description |
|---------------|-------------|
| `restaurant_db.sql` | SQL script to create schema and insert sample data |
| `queries/objective1_explore_menu.sql` | Analyze menu items: categories, prices, and item counts |
| `queries/objective2_explore_orders.sql` | Analyze order patterns, volumes, and activity range |
| `queries/objective3_customer_behavior.sql` | Join data to analyze customer spend, preferences, and top orders |
| `README.md` | This file – project overview and instructions |

---

## 🗃️ Database Schema

### Tables

- **menu_items**
  - Fields: `menu_item_id`, `item_name`, `category`, `price`

- **order_details**
  - Fields: `order_details_id`, `order_id`, `order_date`, `order_time`, `item_id`

---

## 🎯 Project Objectives

### ✅ Objective 1: Explore the Menu
- Count total menu items
- Identify least and most expensive dishes
- Count dishes by category
- Calculate average price per category

### ✅ Objective 2: Explore the Orders Table
- Check date range of orders
- Count total and unique orders
- Find large orders with many items

### ✅ Objective 3: Analyze Customer Behavior
- Join menu and order tables
- Identify most and least ordered items
- Find top-spending orders and explore order makeup

---

## 🚀 How to Use

1. Run `restaurant_db.sql` in your SQL environment (e.g., MySQL Workbench)
2. Run the queries found in:
   - `queries/objective1_explore_menu.sql`
   - `queries/objective2_explore_orders.sql`
   - `queries/objective3_customer_behavior.sql`

---

## 💡 Ideas for Future Work

- Add a customer table to expand the schema
- Analyze spending by time of day or week
- Export results to Power BI or Tableau dashboards
- Build views or stored procedures for reporting

---

## 👤 About the Author

Created by **Nazreen Agos** ([@nazreeninsights](https://github.com/nazreeninsights))  
Aspiring data analyst exploring SQL, Power BI, Tableau & real-world datasets.

---

## 🧠 Skills Demonstrated

- SQL (DDL, DML, joins, GROUP BY, aggregation)
- Relational schema design
- Analytical thinking & query optimization
- Real-world problem solving with structured data
