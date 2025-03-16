# SQL-Project 

## Amazon E-Commerce Data Analysis & Optimization

## Project Overview
This project focuses on analyzing Amazon's e-commerce data using advanced SQL techniques.  
The goal is to optimize database queries, extract key business insights, and enhance decision-making for sales, orders, and seller performance.

## Key Topics Covered
- **Problem Statements** – Addressing 20 key business challenges in e-commerce data analytics.  
- **Joins** – Combining multiple tables (orders, products, sellers, customers) to generate meaningful insights.  
- **Common Table Expressions (CTEs)** – Simplifying complex queries for improved readability and efficiency.  
- **Stored Procedures** – Automating tasks such as identifying inactive sellers, analyzing product performance, and tracking order trends.  
- **Functions** – Creating reusable SQL functions for calculations and data transformations.  

## Project Objectives
- ✅ Identify inactive sellers who haven't received orders in the last 6 months.  
- ✅ Analyze product performance by calculating total sales, order count, and quantity sold.  
- ✅ Track order trends based on status (Completed, Pending, Canceled) and yearly performance.  
- ✅ Optimize SQL queries to enhance performance and reduce execution time.  
- ✅ Automate data retrieval using stored procedures and functions.  

## Expected Outcomes
- ✔ Optimized SQL queries for Amazon's e-commerce data analysis.
- ✔ Automated reports for seller activity, product performance, and order trends.
- ✔ Enhanced decision-making with structured and well-organized data.
- ✔ Improved SQL skills in handling large-scale e-commerce datasets.


## ERD (Entity Relationship Diagram)

![image](https://github.com/user-attachments/assets/d0538e23-32dc-46aa-9be8-9690c6adc32e)

## ERD Relationships

- **Customers → Orders**: One-to-Many (A customer places multiple orders)  
- **Orders → Order_Items**: One-to-Many (Each order can have multiple order items)  
- **Order_Items → Products**: Many-to-One (Each order item refers to one product)  
- **Products → Category**: Many-to-One (Each product belongs to one category)  
- **Sellers → Products**: One-to-Many (Each seller manages multiple products)  
- **Orders → Payments**: One-to-One (Each order has one payment)  
- **Orders → Shipping**: One-to-One (Each order has one shipping record)  
- **Products → Inventory**: One-to-One or One-to-Many (Depending on how inventory is managed)

  ## Data visualization - Power BI
![Sales Performance](https://github.com/user-attachments/assets/a496939b-dcef-400e-ad31-2b5fc0b2d3e4)

![Order Performance](https://github.com/user-attachments/assets/e01e0ab5-bd5f-4712-b5c9-91d546eb5da8)

![Market Performance](https://github.com/user-attachments/assets/1942e2ba-e1dc-4183-9ff2-d6537ed681df)

![Seller Performance](https://github.com/user-attachments/assets/742c9835-d92e-472b-a39e-79a16185850a)

![Forecast Performance](https://github.com/user-attachments/assets/3fc4e17c-e63e-4db5-b628-c35a6a72cb1b)

