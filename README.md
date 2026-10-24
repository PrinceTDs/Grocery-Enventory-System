# Grocery Inventory Management System

A relational database project designed to manage grocery products, warehouses, inventory levels, customers, and sales orders.

### Project Overview
The project models a small grocery inventory and sales environment, transforming a realistic grocery dataset into a structured relational database. The system was designed to support inventory management, order tracking, customer records, and basic business analysis.

### Database Design
The database was designed using **Entity-Relationship (ER) modeling** and translated into a relational schema consisting of six main tables:

- **Material** — grocery products and their prices
- **Warehouse** — storage locations
- **Stock** — product quantities across warehouses
- **Customer** — customer information
- **Orders** — customer purchase transactions
- **OrderItem** — individual products included in each order

Primary keys and foreign keys were used to establish relationships and maintain referential integrity.

### SQL Implementation
The database was implemented in **MySQL Workbench** with an executable SQL script that can recreate the database from scratch.

The project includes:
- Database and table creation
- Primary and foreign keys
- Sample data insertion
- `SELECT` queries
- `JOIN` operations
- Aggregations using `SUM()` and `GROUP BY`
- Subqueries and `HAVING` conditions
- Inventory and sales queries

### Data Analysis
Python was used with **pandas and matplotlib** to perform exploratory analysis on the database data.

The analysis examined:
- Number of orders per customer
- Most frequently ordered products
- Order status distribution
- Stock quantity across warehouses
- Average number of items per order

The analysis found that an average order contains approximately **5.3 items**, while the inventory analysis highlighted differences in stock levels between warehouses. 

### Dataset
The project uses a cleaned and adapted grocery inventory and sales dataset containing:

- **30 products**
- **3 warehouses**
- **15 customers**
- **20 orders**
- Stock records distributed across warehouses
- Order-item records representing purchased products

### Tools & Technologies

**MySQL · SQL · MySQL Workbench · Python · pandas · matplotlib · ER Modeling · Relational Database Design · Data Analysis**
