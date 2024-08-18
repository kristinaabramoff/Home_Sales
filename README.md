# Project Title: Housing Sales Data Analysis with PySpark

## Project Overview

This project demonstrates my expertise in big data processing and analytics using PySpark and Spark SQL. The analysis focuses on housing sales data, where various data processing techniques were applied, in-depth queries were performed, and performance optimization strategies were implemented through caching and partitioning. This project highlights my ability to manage large datasets, derive insights, and improve processing efficiency in real-world scenarios.

## Project Objectives

The key objectives of this project are:

1. **Data Ingestion and Processing**: Load housing sales data from a CSV file stored in an AWS S3 bucket into a Spark DataFrame.
2. **Data Transformation and Cleaning**: Perform data type conversions, extract date components, and clean the dataset for analysis.
3. **Analytical Queries**: Use Spark SQL and DataFrame API to answer business questions, such as trends in home prices and the impact of specific features.
4. **Performance Optimization**: Implement caching and data partitioning to enhance query performance and compare runtimes between cached and uncached operations.
5. **Data Persistence**: Store the processed data in Parquet format, partitioned for efficient querying and storage management.

## Key Features

- **PySpark for Big Data Processing**: Efficient handling of large-scale data using PySpark, with capabilities such as filtering, aggregations, and transformations.
- **Advanced SQL Queries**: Execution of complex queries using Spark SQL to extract actionable insights.
- **Performance Tuning**: Application of caching and partitioning techniques to optimize query performance and resource utilization.
- **Data Storage Optimization**: Saving transformed data in Parquet format, partitioned for better access speed and query efficiency.

## Analysis Questions Answered

The analysis addresses the following key questions:

1. What is the average price for a four-bedroom house sold for each year? (Rounded to two decimal places)
2. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? (Rounded to two decimal places)
3. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? (Rounded to two decimal places)
4. What is the average price of a home per "view" rating, having an average home price greater than or equal to $350,000? (Rounded to two decimal places, with runtime included)

## Technologies and Tools Used

- **Python**
- **Apache Spark (PySpark)**
- **Spark SQL**
- **Parquet Format for Data Storage**
- **AWS S3 for Data Ingestion**
- **Jupyter Notebooks for Analysis and Documentation**

## Installation and Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-url
