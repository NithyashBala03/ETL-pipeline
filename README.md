# ETL-pipeline
Scalable ETL Pipeline for Sales Data in AWS using PySpark


This project demonstrates how to build a robust and scalable data engineering architecture on AWS using PySpark and AWS Glue. The system is designed to process sales data stored in Amazon S3, perform data transformations with PySpark, and load the results into Amazon Redshift for further analytics.

The project showcases the following:

Data Engineering Architecture: Designed with scalability and maintainability in mind using "Infrastructure as Code" (IaC).
ETL Pipeline in PySpark: Built using AWS Glue's Jupyter Notebooks to process and transform sales data.
Dynamic Frames & Spark DataFrames: Practical use of both for efficient data processing.
Redshift Integration: Final processed data is loaded into Amazon Redshift for querying and reporting.

This project processes historical sales data and includes columns such as ID, Region, Country, Item_Type, Sales_Channel, Order_Priority, Order_Date, Order_ID, Ship_Date, Units_Sold, Unit_Price, Unit_Cost, Total_Revenue, Total_Cost, and Total_Profit.

Summary of the Project
The project focuses on building a scalable ETL pipeline to process sales data in AWS.

Data Engineering Architecture:

Uses AWS services like S3, Glue, and Redshift.
Implements Infrastructure as Code (IaC) to ensure scalability and manageability.
Data Pipeline in PySpark:

Reads raw sales data stored in S3.
Processes the data using PySpark transformations such as filtering, aggregations, and data type conversions.
Distinguishes between AWS Glue Dynamic Frames and Spark DataFrames for enhanced flexibility in data processing.
ETL Code:

Extracts raw data from S3.
Transforms it by calculating metrics like total revenue, total cost, and total profit.
Loads the final dataset into Redshift for analytics and visualization.
Use Case:

Demonstrates the processing of real-world sales data with key metrics such as revenue, cost, and profit across different regions, countries, and sales channels.
Technology Stack:

AWS Services: S3 (data storage), Glue (ETL processing), Redshift (data warehouse).
PySpark: For data transformation and processing.
Python: For scripting and implementation.
Output:

A clean, structured dataset loaded into Redshift for further use in dashboards and analytical reports.
