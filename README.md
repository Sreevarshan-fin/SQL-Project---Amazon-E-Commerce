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

  ## Power BI
  ![Market Performance](https://github.com/user-attachments/assets/b9b4fda3-5f2f-470e-b2ed-26e41645b93e)
  
