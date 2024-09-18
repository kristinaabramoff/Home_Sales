# Housing Sales Data Analysis with PySpark

## Project Overview
This project showcases the use of **PySpark** and **Spark SQL** to process and analyze large-scale housing sales data. Various data processing techniques, analytical queries, and performance optimization strategies were applied. Through this project, I demonstrate my ability to handle big data, derive actionable insights, and enhance query performance through caching and partitioning.

## Project Objectives
The key objectives of this project are:
- **Data Ingestion and Processing**: Load housing sales data from a CSV file stored in an AWS S3 bucket into a Spark DataFrame.
- **Data Transformation and Cleaning**: Perform data type conversions, extract date components, and clean the dataset for analysis.
- **Analytical Queries**: Use Spark SQL and DataFrame API to answer business questions, such as trends in home prices and the impact of specific features.
- **Performance Optimization**: Implement caching and data partitioning to enhance query performance and compare runtimes between cached and uncached operations.
- **Data Persistence**: Store the processed data in Parquet format, partitioned for efficient querying and storage management.

## Key Features
- **PySpark for Big Data Processing**: Efficient handling of large-scale data with filtering, aggregations, and transformations.
- **Advanced SQL Queries**: Complex queries executed using Spark SQL to extract actionable insights.
- **Performance Tuning**: Caching and partitioning techniques were used to optimize query performance and resource utilization.
- **Data Storage Optimization**: Saving transformed data in Parquet format, partitioned for better access speed and query efficiency.

## Analysis Questions Answered
The analysis addresses the following key questions:
1. **Average Price for Four-Bedroom Homes Sold Each Year**: Rounded to two decimal places.
2. **Average Price of Homes Built Each Year with Three Bedrooms and Three Bathrooms**: Rounded to two decimal places.
3. **Average Price of Homes Built Each Year with Three Bedrooms, Three Bathrooms, Two Floors, and ≥ 2,000 Sq. Ft.**: Rounded to two decimal places.
4. **Average Price of Homes per "View" Rating with an Average Price ≥ $350,000**: Rounded to two decimal places, with runtime included.

## Technologies and Tools Used
- **Python**
- **Apache Spark (PySpark)**
- **Spark SQL**
- **Parquet Format for Data Storage**
- **AWS S3 for Data Ingestion**
- **Jupyter Notebooks for Analysis and Documentation**

## Accessing the Code
The full code for this project can be accessed in the `Home_Sales_starter_code_colab1.ipynb` notebook in the repository. This notebook contains all the steps for data ingestion, transformation, analysis, and optimization.

## Installation and Setup Instructions
To run this project on your local machine, follow these steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/kristinaabramoff/Home_Sales.git

