# ETL-pipeline
Scalable ETL Pipeline for Sales Data in AWS using PySpark
This project demonstrates how to build a robust and scalable data engineering architecture on AWS using PySpark and AWS Glue. The system is designed to process sales data stored in Amazon S3, perform data transformations with PySpark, and load the results into Amazon Redshift for further analytics.

The project showcases the following:

Data Engineering Architecture: Designed with scalability and maintainability in mind using "Infrastructure as Code" (IaC).
ETL Pipeline in PySpark: Built using AWS Glue's Jupyter Notebooks to process and transform sales data.
Dynamic Frames & Spark DataFrames: Practical use of both for efficient data processing.
Redshift Integration: Final processed data is loaded into Amazon Redshift for querying and reporting.
This project processes historical sales data and includes columns such as ID, Region, Country, Item_Type, Sales_Channel, Order_Priority, Order_Date, Order_ID, Ship_Date, Units_Sold, Unit_Price, Unit_Cost, Total_Revenue, Total_Cost, and Total_Profit.
