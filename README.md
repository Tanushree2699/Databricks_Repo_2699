# Retail Data Engineering & Lakehouse Platform

An end-to-end cloud data engineering solution built using **AWS and Databricks** to automate data ingestion, transformation, quality validation, and historical data processing for retail analytics.

## Overview

This project implements a scalable data platform where file arrivals in **Amazon S3** trigger **AWS Lambda**, which orchestrates Databricks jobs for near-real-time data ingestion and processing.

The platform follows a layered data architecture across **Raw, Lake, Hub, and Mart** layers, enabling reliable and analytics-ready data for downstream reporting.

## Key Features

- Event-driven data ingestion using **Amazon S3 and AWS Lambda**
- Automated orchestration of **Databricks jobs**
- Data quality validation and error handling
- Duplicate record detection
- Schema enforcement and validation
- **SCD Type 2** processing for historical data tracking
- Layered data architecture: **Raw → Lake → Hub → Mart**
- Automated downstream transformations
- Analytics-ready datasets for business reporting

## Technology Stack

- **Cloud:** AWS
- **Data Platform:** Databricks
- **Storage:** Amazon S3
- **Orchestration:** AWS Lambda, Databricks Jobs
- **Processing:** Apache Spark / PySpark
- **Data Management:** Delta Lake
- **Architecture:** Raw, Lake, Hub, Mart
