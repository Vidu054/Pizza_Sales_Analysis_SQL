# Pizza_Sales_Analysis_SQL

## Introduction

In today's data-driven world, understanding consumer preferences and market trends is essential for businesses to stay competitive. In this analysis, we delve into the Pizza dataset to uncover valuable insights into the dynamics of the pizza industry.

Context:
The pizza industry is a significant player in the global food market, with various offerings ranging from traditional classics to innovative creations. As consumer tastes evolve and competition intensifies, it becomes increasingly important for pizza businesses to adapt and innovate to meet the market's demands.

## About Dataset

This pizza sales dataset is made up 12 relevant features:

**order_id:** Unique identifier for each order placed by a table

**order_details_id:** Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)

**pizza_id:** Unique key identifier that ties the pizza ordered to its details, like size and price

**Quantity:** Quantity ordered for each pizza of the same type and size

**order_date:** Date the order was placed (entered into the system before cooking & serving)

**order_time:** Time the order was placed (entered into the system before cooking & serving)

**unit_price:** Price of the pizza in USD

**total_price:** unit_price * quantity

**pizza_size:** Size of the pizza (Small, Medium, Large, X Large, or XX-Large)

**pizza_type:** Unique key identifier that ties the pizza ordered to its details, like size and price

**pizza_ingredients:** ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce unless another sauce is specified)

**pizza_name:** Name of the pizza as shown in the menu

## Problem Statement 

1. Identify trends and patterns in pizza sales, including popular pizza, customer preference, Size and peak ordering times.

2. Provide actionable insights.

### KPI Requirement
We need to analyse key indicators for our Pizza sales data to gain insight into our business performance. Specifically, we want to calculate the following metric:

1. **Total Revenue:** The sum of the total price of all pizza orders.
2. **Average Order Value:** The average amount spent per order, is calculated by dividing the total revenue by the total number of orders.
3. **Total Pizza Sold:** The sum of the quantities of pizza sold
4. **Total Orders:** Total number of orders placed by the customers.
5. **Average Pizza Per Order:** The average no of pizzas that are ordered in each transaction, is calculated by dividing the total number of pizzas sold by the total number of orders.

I will also try to answer below question

1. During which days and times do we experience the highest activity levels?
2. How many pizzas are produced during peak periods?
3. Which pizzas are our top sellers and which ones perform poorly?
4. What is the average revenue generated?
5. How does our order performance vary every month?
6. What is the performance of different pizza sizes in terms of orders?
7. Which pizza category is the most popular among customers?
8. How does our monthly revenue performance compare?







