SQL Queries for Profit Margin Analysis of Nike Products
This repository contains SQL scripts designed to analyze the profit margins of products from Nike, focusing on various business insights. The queries address multiple business questions, including the expected profit margins, distribution center performance, and profit margins across different product lines and time periods.
Queries Overview
1. Expected Profit Margin for Each Product
    * Calculate the expected profit margin for each product.
    * Flag products as either "Nike Vintage" or "Nike Official" based on their names.
    * Group and display products with their respective profit margins and business units.
2. Profit Margin by Distribution Center
    * Calculate the average profit margin for each distribution center.
    * Identify any distribution centers that stand out in terms of profit margin.
3. Real Profit Margin for Specific Nike Official Products
    * Calculate the real profit margin for specific products: Nike Pro Tights, Nike Dri-FIT Shorts, and Nike Legend Tee.
    * Display the profit margins for these products.
4. Real Profit Margin Split by Date
    * Calculate the real profit margin for products.
    * Split the data based on the created date: before and after May 1, 2021.
5. Profit Margin by Product for Nike Official and Nike Vintage
    * Calculate the profit margin for both Nike Official and Nike Vintage products.
    * Provide a single view of profit margins across all products.
6. Top 10 Products by Profit Margin
    * Identify the top 10 products by profit margin.
    * Include the product name, profit margin, and business unit (Nike Official or Nike Vintage).
Detailed SQL Scripts
The SQL scripts are written to work with a relational database containing tables such as products, order_items, orders, and distribution_centers. The queries utilize JOIN operations to combine data from multiple tables and perform calculations to derive the desired insights.
