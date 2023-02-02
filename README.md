# Exploratory-Data-Analysis Projects

# Project 1: Sales Analysis 

This is a project I worked on to practise my skills on Data Cleaning and Exploration.

In this project,I used Python pandas and Python Matplotlib to analyze and answer business questions. The dataset contains 187,000 records broken down by Product type, Quantity Ordered,Order Date,Product Price and Purchase Address.

I performed data cleaning by :
- checking for missing values and dropping where necessary
- adding columns(month,sales and state) by extracting from columns provided
- converting columns with wrong datatypes to the correct ones(to_datetime,to_numeric)

After cleaning and confirming, I proceeded to exploring my data and getting necessary information to answer the business questions:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer the business questions,I walked through different pandas and matplotlib methods which includes:
- merging 12 months data into a single csv file
- adding columns by extracting from given columns
- using .apply() method 
- using .groupby() to aggregate according to a category
- using .sort_values() to sort values in a descending manner
- using .unique() to the unique values in a column
- plotting bar charts and lines graphs to visualize the results
- labelling the graphs




# Project 2: AngiesBerryCorner 

This project contains SQL queries written to query a fruit store's database for key insights to help retailers market better and effectively, and to establish trends that help them capitalize on customer behaviour.

Data Source:

The dataset was gotten from https://www.techchak.com/ and it contains four tables:  **customer**, **employee**, **transaction**, and **product**.
- customer table contains information of all Angie Berry's customer first and last names and their unique ids. 
- employee table has the list of all 10 employees, start date, and end date if they have resigned or been fired.
- transaction table which contain a list of the last 100,000 transactions as of 19th August 2019 and attributes (id, customer_id, product_id, quantity, paid_at, Amount) 
-  product table which has the names of all 12 products currently sold, the product_id, unit, and product price.


### Background

Angie’s Berry corner is a fruit store located in LA and has sorted the help of the data science and analytics team to extract data from their data warehouse to answer business questions about their recent upswing in sales.
We were provided with 4 tables presented in an excel format namely: 
- transaction_report with columns (id, customer_id, product_id, quantity, paid_at, Amount) which contain a list of the last 100,000 transactions as of 19th August 2019.
- loyalty_customers which has the name of all their customers and id.
- product table which has the name of all 12 products currently sold, id, unit, and price.
- employee table  which contains the list of all 10 employees, start date, and end date if they have resigned or been fired.

### Methodology
- Since Angie’s Berry corner has no active database, a database was created, 4 tables were created within the database, and data was stored in the tables using the copy command method in PostgreSQL.
- Wrote SQL codes to extract data that answer business questions.


### Questions
This analysis will answer the following questions:
1. What's Angie’s Berry Corner’s average daily sales volume?
2. Which products sell best?
3. Who are the top 5 Angie loyalty customers?
4. What's the full name of their current staffs?
5. What's the product that generates the least income and by much?
6. How much does the organization realize from sales?
7. How much does the organization realize from each product?
8. What's the product that generates the highest income and by much?
9. Which customers patronize Angie Berry the most?
10. Which customer generate least income and by how much?
11. Which of the employees spent the least day at angie?
12. What's the organization's busiest hour?
13. What's the organization's busiest day of the week?
14. What's the organization's busiest month of the year?



# Project 3: HealthCare 

# Project 4: VacatStores-Analysis

### Background
Vacat Stores is an ecommerce retail industry that helps to solve the needs of the people of the United States and with the help of the science and analytics team seek to develop an analytics dashboard that would track and monitor KPI metrics towards the business goals and help them derive real-time insights for informed decision making to help drive growth.


### Goal
In this project, the goal is to:
1. Perform ETL process, build a data model and apply statistical methods to the dataset.
2. Analyze the dataset and transform it into an analytics dashboard to help Vacat Stores track and monitor the KPI metrics towards their business goals and derive real-time insights to inform decision making to aid growth.
3. Significantly reduce reporting time by automating the report process.

### Methodology
1. Datasets was aggregated from disparate sources (PostgreSQL, Salesforce and ERP system) into a centralized platform which solves the data silo problems.
2. SQL queries was used to  extract datasets from the relational database management system (PostgreSQL).
3. Dataset was extracted, transformed by ensuring correct data type for each column, loaded and built a data model by connecting the  common column in each table using PowerBI.
4. Performed descriptive analysis to help understand the summary of the datasets by applying  statistical calculations using DAX functions.
5. Performed exploratory analysis by using historic data extracted from the relational database system to identify patterns, trends, outliers, relationships, and rankings.
6. Correlation analysis was performed to show relationship between discount and orders. 
7. Developed interactive dashboards by using appropriate graphs and charts to represent the data.

### Questions
Some of the business questions to be investigated are:
1. What are the best-selling products?
2. In what category is the store not profitable?
3. What state has the highest number of Customers and generated the  highest revenue?
4. Does  Discount have an impact on the number of Orders received?
5. How are deliveries trending overtime?
6. What's the distribution of Order shipment category?
7. Which segment of our customers generated the highest profit and revenue?







# Project 4: Sales Transaction 
