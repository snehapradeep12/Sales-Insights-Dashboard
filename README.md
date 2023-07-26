## Sales-Insights-Dashboard

![image_dashboard](https://github.com/snehapradeep12/Sales-Insights-Dashboard/assets/69630009/61e9582f-e45d-4321-828d-e67bdd40fb17)

#### Data Used - Sales Data for a Hardware Store company from the year 2017 to 2020 consisting of tables on sales transactions, sales markets, sales products, sales date, and customers.With the sales transactions table having over 1 Lakh rows on sales amount, sales qty, consumer code, etc.

Data Transformation and Visualization - PowerBI

Data Analysis - MySQL Workbench

#### Business Questions:
1.	How many customers does the company have?
2.	What is the distribution type of the customers and their respective revenue generated?
3.	What is the sales revenue trend of the Company?
4.	Which month has shown the highest Sales order Volume?
5.	Which zone has grossed the highest revenue for the company?
6.	Which individual markets in the North had the highest Sales Order Volume?
7.	What is the minimum and maximum order size for a sales revenue greater than Rs 10k?

#### Summary of Findings
1.	There are a total of 38 customers across different regions for this company
2.	Customers who own a Brick and Mortar have purchased more products from the company indicating that offline sales channels have been more profitable for the company than online sales through e-commerce websites.
3.	The revenue for the year 2018 has been the highest compared to all the other years. We can also note that there has been a steep decline in revenue through the years 2018 to 2020.
4.	An increase in the order placed and purchase of products occurred in the month of November and January followed by October.
5.	North Zone has generated the highest revenue followed by the Central and South Zone respectively.
6.	Delhi NCR has generated the highest Order size as compared to the markets in other North regions such as Surat, Kanpur, Patna, etc.
7.	The maximum order size for a customer is 14049 while the minimum order size is 3.



#### Limitations

Some records in the transactions table had Sales Quantity column values as -1 and 0 (950 records) even in the cases where the sale of a product was registered.

Few records were international transactions (less than 100) and thus had no zone i.e North, South and Central pertaining to the indian cities as value to the Zone column in the markets table. These were Null values and had to be removed from the dataset.





