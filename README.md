# advanced-sql-sales-analysis

This project focuses on advanced SQL analysis techniques to analyze sales data. 
It demonstrates the use of JOINs, subqueries, CTEs, window functions, and aggregations 
to extract meaningful business insights from transactional data.



## Objective

- Analyze customer purchasing behavior
- Identify top customers and products by revenue
- Rank customers and products using window functions
- Perform city-wise and customer-wise sales analysis
- Handle missing data using COALESCE




## Dataset

The database consists of the following tables:

### Customers
- customer_id (Primary Key)
- customer_name
- city

### Products
- product_id (Primary Key)
- product_name
- price

### Orders
- order_id (Primary Key)
- customer_id (Foreign Key)
- product_id (Foreign Key)
- quantity
- order_date




## SQL Concepts Used

- INNER JOIN
- LEFT JOIN
- GROUP BY & HAVING
- Aggregate Functions (SUM, COUNT)
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions (RANK, DENSE_RANK)
- PARTITION BY
- COALESCE
- Foreign Key Relationships




## Key Analysis Performed

### 1. Customer-wise total spend
- Calculated total amount spent by each customer
- Ranked customers based on spending

### 2. Product performance analysis
- Identified top-selling products by quantity
- Calculated total revenue per product
- Ranked products using window functions

### 3. City-wise customer ranking
- Ranked customers within each city based on total spend

### 4. Customers with no orders
- Used LEFT JOIN and COALESCE to identify inactive customers



## Sample Output

| Customer Name | City      | Total Spend | Rank |
|--------------|-----------|-------------|------|
| Amit         | Mumbai    | 56000       | 1    |
| Rahul        | Bangalore | 50000       | 2    |
| Riya         | Delhi     | 20000       | 3    |
| Suresh       | Pune      | 7500        | 4    |



## Tools Used

- PostgreSQL
- pgAdmin 4
- SQL (Advanced Queries)
  
## Version Control
- Git & GitHub (Project Repository & Documentation)




## How to Run

1. Create a PostgreSQL database
2. Run table creation scripts
3. Insert sample data
4. Execute analysis queries in pgAdmin


## Conclusion

This project demonstrates practical, industry-relevant SQL skills required for data analysis roles. 
It showcases the ability to work with real-world datasets, write optimized queries, and derive 
business insights using advanced SQL concepts.



## Author

**Sandesh Pal**  
📍 Navi Mumbai  
📧 sandeshpal2201@gmail.com  
🔗 GitHub: https://github.com/sandeshpal2201-SAN

