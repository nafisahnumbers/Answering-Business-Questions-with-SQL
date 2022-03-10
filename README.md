# Answering Business Questions with SQL
In this project, I accessed a company's database and answered business questions using SQL queries.
The company sells buys and sells food items. It has suppliers and customers (companies) from various countries around the world. 
The head of the sales department wanted to know the following:
1. Who were the top 10 customers and how much had they spent and ordered?
2. What were the top customers’ favorite products?
3. Where were th customers mostly located, and how much was the total spend per country?
4. What were the top 10 most popular products?
5. Who were the suppliers for the most popular products?
6. Who were the top 3 best performed Employees?

I downloaded the database and used DB Browser to access the database tables and run the (SQLite) queries. To answer the questions, I used data fron these tables:
- Products: This table contains the names of all the products the company sells, their product IDs, and other important imformation.
- Orders: This table contains information about every order; the order ID, the customer ID, the order date, shipping date and more.
- OrderDetails: This table contains information about each product that was ordered. This table is necessary because a customer can order for multiple products at once. The name and price of the product, quantity ordered and discount are in this table.
- Customers: This table contains details about each customer; their company name, contact (person) name, customer ID, location, telephone, etc.
- Employees: This table contains employee biodata

The text file contains the code I used to query the stores database and retrieve information to answer the questions above. It also contains dashboards with important visualizations done with Power BI
