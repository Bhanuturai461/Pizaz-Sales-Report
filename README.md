# Pizaz-Sales-Report

**Project Overview**

This project analyzes one year of pizza sales data to uncover key business insights such as revenue trends, customer ordering behavior, top-performing products, and category-wise performance.
The analysis was performed using SQL for data exploration and Power BI for interactive dashboard creation.

The goal of the project is to provide a data-driven understanding of sales performance, identify improvement opportunities, and support business decision-making.


**Dataset Description**

The dataset represents transactional-level pizza sales data. Each row corresponds to an item sold in an order and includes details such as:

•Order information (Order ID, Order Date, Time)
•Product details (Pizza Name, Category, Size)
•Sales metrics (Quantity, Total Price)
•Source: Pizza Sales Dataset (CSV)


**Key Attributes Include**

| Column Name        | Description                                  |
| ------------------ | -------------------------------------------- |
| **order_id**       | Unique identifier for each order             |
| **order_date**     | Date when the order was placed               |
| **order_time**     | Time when the order was placed               |
| **pizza_name**     | Name of the pizza                            |
| **pizza_category** | Category (Classic, Chicken, Supreme, Veggie) |
| **pizza_size**     | Size (S, M, L, XL, XXL)                      |
| **quantity**       | Number of units sold                         |
| **total_price**    | Total price for the line item                |


**Business Objectives**

The main business objectives of this analysis are:

•Understand Overall Sales Performance
Track revenue, total orders, and pizzas sold.
Calculate average order value and average pizzas per order.

•Identify Trends Over Time
Daily and monthly patterns in ordering behavior.
Identify peak and low sale periods.

•Analyze Category & Size Performance
Which pizza category contributes the most?
Which size generates maximum sales?

•Evaluate Product-Level Insights
Identify top & bottom pizzas by:
Revenue
Quantity
Number of orders

•Support Business Decisions
Improve marketing strategies
Optimize inventory
Identify best-selling categories and pizza types


**Key Business Questions Answered**

Here are the major questions solved using SQL and Power BI:

1. What is the total revenue generated?
2. What is the average order value?
3. How many total pizzas were sold?
4. What are the total number of orders?
5. How many pizzas are ordered per order on average?
6. What are the daily and monthly ordering trends?
7. Which pizza category contributes the most to revenue?
8. Which pizza size generates maximum sales?
9. What are the best- and worst-selling pizzas?


***Product Analysis***

**• Sales by Pizza Category**

Using SQL queries on category revenue and quantity:

Classic category leads in both revenue & number of orders.

Veggie and Supreme categories follow next.
(Reference: Category Revenue Query) 

Pizza_Sales_Sql_Queries

**• Sales by Pizza Size**

Large (L) pizzas contribute the highest revenue share.

Medium (M) and Regular (S) sizes follow.

XX-Large contributes the least due to limited demand.

**• Best-Selling Products**

Based on top 5 queries:

Certain Classic pizzas dominate revenue and orders.

High-performing pizzas are consistent across quantity & revenue metrics.

**• Least-Performing Products**

From bottom 5 queries:

A few niche pizzas (specialized flavors) have low demand.

Smaller business opportunity in these items.

**• Ordering Behavior**

Weekends (Friday, Saturday) show the highest order volume.

Monthly trends show peaks in July and January.


**Deliverables**
<img width="565" height="320" alt="Pizza_Sales_Report" src="https://github.com/user-attachments/assets/86b2c722-44dc-44fe-b40b-69915a0c4380" />


