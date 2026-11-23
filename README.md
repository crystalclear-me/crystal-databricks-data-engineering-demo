# crystal-databricks-data-engineering-demo


# Banking Transaction ETL Pipeline

## Project Overview

This project demonstrates an end-to-end banking transaction data engineering pipeline using Databricks, PySpark, Spark SQL and Delta Lake.

The project simulates the ingestion and processing of daily banking transactions from a fictional core banking system.

## Business Objectives

- Ingest banking transaction records.
- Preserve original source data.
- Identify duplicate transaction records.
- Validate customer information and transaction amounts.
- Transform raw data into structured datasets.
- Prepare business-ready transaction analytics.

## Technologies

- Databricks Free Edition
- Python
- PySpark
- Spark SQL
- Delta Lake
- GitHub

## Project Architecture

The pipeline follows the Medallion Architecture:

1. Bronze: Raw banking transaction ingestion.
2. Silver: Data cleansing, validation and deduplication.
3. Gold: Aggregated datasets for reporting and analytics.

## Project Progress

### Completed
- Databricks environment setup.
- Synthetic banking transaction dataset creation.
- PySpark DataFrame creation.
- Initial data profiling.
- Bronze Delta table ingestion.
- Bronze record count and data preservation validation.

### Upcoming
- Silver data cleansing and transformation.
- Invalid transaction identification and rejection handling.
- Data quality testing.
- Gold transaction analytics.
- Pipeline automation and monitoring.

## Data Disclaimer

All transaction records are synthetically generated for educational and portfolio demonstration purposes. No actual customer or banking information is used.
