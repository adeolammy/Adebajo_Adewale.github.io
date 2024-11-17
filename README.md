# Data Analytics Portfolio
# Project 1

**Title: Tools:** [Adidas Sales Dashboard](https://github.com/adeolammy/Adebajo_Adewale.github.io/blob/main/Adidas-Dashboard-START.xlsx)

**Used: Project:** Microsoft Excel (Pivolt table, Pivolt Chart, Filters and Slicers and timelines, Conditional Formatting)

**Description:** This project involves analyzing Adidas sales data to provide a detailed and interactive dashboard for tracking sales performance across different dimensions. The dashboard serves as a powerful tool for visualizing sales trends and supporting strategic decision-making.

Key Features of the Dashboard:
Retailer Performance

A bar chart showcasing total sales by retailer, enabling stakeholders to identify high-performing partners like Amazon, Foot Locker, and Walmart.
Regional Insights

A regional sales chart highlighting performance in different parts of the U.S. (e.g., Midwest, Northeast, Southeast, etc.), helping to pinpoint strong and underperforming regions.
Sales Method Distribution

A pie chart summarizing sales contributions from various methods (In-store, Online, Outlet), providing insights into channel effectiveness.
Product Sales Analysis

A breakdown of sales performance across product categories (Men's and Women's Apparel, Footwear) using a comparative bar chart.
Total Sales Trends

A dynamic line graph displaying total sales trends over time, giving an overview of sales growth and consistency.
Interactive Slicers:
The dashboard includes several filters for detailed analysis:

Retailer: Focus on specific retail partners like Amazon or Foot Locker.
Region: Analyze performance by geographical areas in the U.S.
Product: Drill down into specific product categories to understand their contributions.
Sales Method: Filter data based on in-store, online, or outlet sales.
Objective and Benefits:
This dashboard enables Adidas to:

Track Key Performance Metrics: Monitor and analyze performance across various dimensions in real-time.
Identify Opportunities for Growth: Uncover insights into underperforming regions or channels.
Support Data-Driven Decisions: Inform strategic initiatives such as marketing campaigns, resource allocation, and inventory management.
Developed with interactivity and usability in mind, this dashboard is a vital tool for Adidas to enhance operational efficiency and achieve its business goals.

**Key findings:** 
Top-Performing Retailers:

Retailers like West Gear and Kohl’s generated the highest sales volumes, indicating strong partnerships and effective distribution in these channels.
Sports Direct and Walmart showed lower sales performance, suggesting potential areas for improvement in collaboration or market penetration.
Regional Sales Insights:

The West region leads in total sales, demonstrating significant market dominance.
The Northeast and Southeast regions exhibit moderate performance, while the Midwest and South regions lag behind, presenting opportunities for targeted marketing and sales strategies.
Product Performance:

Men's Athletic Footwear and Men’s Apparel dominate sales, reflecting customer preference and strong market demand in these categories.
Women’s Street Footwear shows lower performance, signaling a need for improved marketing or product offerings for women.
Sales Method Analysis:

In-store sales account for the largest portion of total sales, emphasizing the importance of physical retail locations.
Online sales contribute significantly but still trail behind in-store sales, indicating growth potential in e-commerce.
Outlet sales form the smallest share, suggesting limited reach or appeal of this sales channel.
Seasonality and Trends:

Sales trends show fluctuations across the year, with peak sales periods aligning with holidays or promotional seasons. Identifying these trends 
can help optimize inventory and marketing efforts during high-demand months.
Consistent sales in some regions suggest loyal customer bases, while sporadic trends in others may indicate unstable market engagement.
Profitability Insights:

While total sales figures are high, operating margins vary significantly between regions and products, signaling a need to optimize cost structures in underperforming areas.
Regions with lower profitability, despite high sales, may benefit from improved operational efficiencies or pricing strategies.
Opportunities for Growth:

Underperforming products and regions, such as Women’s Footwear and the Midwest region, highlight opportunities for targeted investments, such as product diversification and localized marketing.
E-commerce presents a significant growth avenue, especially with shifting consumer behavior towards online shopping.

**Dashboard Overview**
![Adidas_dashboard](Adidas_dashboard.png)




# Project 2

**Title:** Inventory management system

**SQL Code:** [Inventory management system Sql Quaries](https://github.com/adeolammy/Inventory-management-system/blob/main/Inventory_management_system.sql)

**SQL Skills Used:** 

Database Creation and Management:

--Designed and created a relational database using **CREATE DATABASE** and **USE** commands.

--Established a structured schema for effective data storage and retrieval.

Table Design and Creation:

--Used **CREATE TABLE** to define tables for brands, products, stores, transactions, and more.

--Added constraints like **PRIMARY KEY, FOREIGN KEY, and REFERENCES** to ensure data integrity.

Data Insertion:

--Inserted records into tables using **INSERT INTO** statements.

--Populated tables with sample data for brands, categories, products, and transactions.

Data Retrieval (SELECT):

--Queried data from multiple tables using **SELECT** to extract specific information.

Data Filtering:

--Applied filters using **WHERE, BETWEEN, IN, and logical operators like AND/OR**.

Data Aggregation:

--Used functions like **SUM, COUNT, and AVG** to calculate totals, averages, and counts for analysis.

Data Updating:

--Updated records using UPDATE to reflect changes in store names or product prices.


--Linked multiple tables with **FOREIGN KEY** constraints to maintain relationships.

--Combined data from multiple tables using **JOIN** to retrieve cross-referenced information.

Transaction Management:

--Created a transactions table to record and analyze sales, payments, discounts, and dues.

Database Normalization:

--Organized tables to minimize redundancy and ensure efficient data retrieval.

Data Constraints:

--Enforced data integrity using **NOT NULL, PRIMARY KEY, and FOREIGN KEY** constraints.

Data Deletion:

Removed unnecessary or outdated data using **DELETE or DROP**.


Utilized **TIMESTAMP and CURRENT_DATE()** to capture dates for user activity and product additions.

Error Handling in Data Relationships:

--Ensured consistent data relationships when inserting, updating, or deleting records.

These SQL skills demonstrate a strong foundation in database management, query optimization, and relational database design, 
enabling efficient handling of complex data operations. Let me know if you'd like to elaborate on any specific skills!






**Project Description:** This project involves designing and implementing a robust SQL-based inventory management system to streamline operations, track inventory, and manage customer transactions. The system is designed to support efficient data retrieval, storage, and manipulation through a structured relational database.

Key Objectives:
Efficient Data Management: Provide a scalable database structure for storing inventory, users, products, and transaction data.
Data Analysis & Insights: Facilitate data aggregation and filtering for performance insights.
Comprehensive Operations Support: Track sales, inventory levels, customer activity, and store-specific data.

Database Design:
The inventory management system is built on a relational database schema with the following key components:

-Brands Table: Stores brand information (e.g., Samsung, Nike).  

-Inventory Users Table: Manages user credentials, roles (Admin, Sales, etc.), and login activities.

-Category Table: Defines product categories (Electronics, Clothing, etc.).

-Product Table: Tracks product details such as stock, pricing, and categories.

-Stores Table: Captures store details, including addresses and contact numbers.

-Providers Table: Links brands and stores, incorporating discounts.

-Customers Cart Table: Tracks customer information and cart data.

-Select Product Table: Records product selection by customers with quantities.

-Transactions Table: Stores transactional data, including payment details and outstanding dues.

-Invoice Table: Contains details of purchased items and their prices.

Key Features:

Comprehensive Data Management:
-Handles end-to-end data related to brands, products, customers, stores, and transactions.

Interactive Querying:
-Supports advanced filtering, aggregation, and cross-table querying

Inventory Control:
-Tracks stock levels, pricing, and product movement between stores.

Transaction Tracking:
-Records and manages payment details, discounts, and dues.


Benefits:
-Improved Operational Efficiency: Automates data management and reduces manual errors.

-Scalable Structure: Supports future expansion of stores, products, and customers.

-Enhanced Decision-Making: Provides actionable insights from transactional and inventory data.


This project demonstrates an end-to-end SQL implementation of an inventory management system that 
integrates user authentication, stock control, and transaction monitoring. 



**Technology used:** SQL server
