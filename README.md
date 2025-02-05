# Home Sales Data Analysis with PySpark and SparkSQL
### Project Overview
I used PySpark and SparkSQL to analyse home sales data in this project. The goal was to determine key metrics, such as average prices of homes, based on different attributes like the number of bedrooms, bathrooms, and square footage. The analysis was performed on a dataset that contains home sales information, and I utilised several SparkSQL functions to extract insights.
### Tools Used
- Google Colab: For writing and running the code.
- PySpark: For handling and processing large-scale data using SparkSQL.
### Key Features
- Data Loading and Temporary Views: I loaded the home sales data from an S3 bucket and created a temporary view for further SQL-based analysis.
- SQL Queries: I ran SQL queries to compute the average home prices based on various conditions (e.g., bedrooms, square footage, view ratings).
- Performance Optimisation: I optimised query performance by partitioning the data, caching tables, and comparing query runtimes.
- Data Partitioning: I partitioned the data by year and saved it in Parquet format for efficient querying.
- Caching and Uncaching: I cached the temporary table to speed up repeated queries and verified the caching status.

#### This repository is for Soheil Dabooyeh's Home_Sales challenge for Monash Data Analytics Bootcamp.
