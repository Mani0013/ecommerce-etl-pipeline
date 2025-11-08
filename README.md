# E-commerce ETL Pipeline with PySpark and Databricks

## Project Overview
An end-to-end ETL pipeline processing e-commerce data using PySpark on Databricks. This project demonstrates data ingestion, transformation, Delta Lake storage with time travel, and star schema modeling for analytics.

## Technologies Used
- **Apache Spark**: PySpark for distributed data processing
- **Databricks**: Unified data analytics platform
- **Delta Lake**: Reliable data lakes with ACID transactions
- **Python**: Data transformation and analysis
- **SQL**: Data querying and analysis
- **Git**: Version control

## Dataset
Brazilian E-commerce Dataset from Olist
- Contains multiple CSV files: orders, customers, products, order items
- Real-world e-commerce transactions
- Perfect for building dimensional models

## Project Architecture

### ETL Pipeline Steps:
1. **Data Ingestion**: Load raw CSV files into PySpark DataFrames
2. **Data Cleaning**: Handle missing values, deduplication, type casting
3. **Data Transformation**: Feature engineering, data enrichment
4. **Delta Lake Storage**: Write cleaned data to Delta tables
5. **Time Travel Demonstration**: Query historical data versions
6. **Star Schema Modeling**: Create fact and dimension tables

## Key Features
- **Scalable Processing**: Handles 2GB+ of e-commerce data using PySpark
- **Data Quality**: Implements data validation and cleaning routines
- **Delta Lake Advantages**: ACID transactions, time travel, schema evolution
- **Optimized Analytics**: Star schema design for efficient querying
