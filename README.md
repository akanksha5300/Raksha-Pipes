This project involves building a data management and visualization system for Raksha Pipes. The system includes generating realistic data, designing a MySQL database, and creating an interactive dashboard using Power BI. The aim is to provide valuable insights to help Raksha Pipes make informed business decisions. 
Step 1: Generate Data and Design Database
Generate Data
I used the faker library in Python to generate realistic data for the following tables:

Product: Information about the products sold by Raksha Pipes.
Customer: Details of the customers purchasing the products.
Order: Information on customer orders.
Shipper: Details of the shipping companies delivering the products.
Review: Customer reviews of the products.
OrderDetails: Detailed information about each order.
Payment: Payment details for the orders.
The data generation script can be found in the data_generation.py file.

Design Database
Designed a MySQL database schema with the following interconnected tables to avoid redundancy and ensure data integrity:
Product
Customer
Order
Shipper
Review
OrderDetails
Payment

Step 2: Set Up Database in MySQL
The generated data was used to populate the designed MySQL database. SQL scripts were created to build the database schema and insert the data.

Step 3: Create Dashboard in Power BI
Created an interactive dashboard is in Power BI to visualize key business metrics. The dashboard connects to the MySQL database and displays:

Sales Trends: Visualizations showing sales over time.
Product Performance: Insights into how different products are performing.
Customer Profiles: Information on customer demographics and buying patterns.
Here’s a screenshot
![Screenshot (44)](https://github.com/akanksha5300/Raksha-Pipes/assets/156895186/349443cf-740c-4731-9a2f-fd596276aa31)



