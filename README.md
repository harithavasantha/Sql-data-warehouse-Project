# About Me

Hi, I'm Haritha 👋  
I am passionate about Data Engineering, SQL, and Data Warehousing.  
This project demonstrates my understanding of ETL pipelines, Medallion Architecture, and SQL-based data transformation techniques.

---

# Data Warehouse using SQL and Medallion Architecture

This project demonstrates how to build a **basic Data Warehouse** using **SQL** and **CSV files** by implementing the **Medallion Architecture** approach. The goal of this project is to simulate a real-world data engineering workflow where raw data is ingested, cleaned, transformed, and organized into meaningful analytical layers.

---

# Architecture Overview

## Bronze Layer – Raw Data

The Bronze layer stores the original CSV data exactly as received from source systems.  
This layer acts as the landing zone for raw datasets and preserves historical data without modifications.

### Purpose
- Store raw and unprocessed data
- Maintain data integrity
- Enable data traceability and auditing

### Source
- CSV files

---

## Silver Layer – Cleaned & Transformed Data

The Silver layer contains cleaned, standardized, and transformed data derived from the Bronze layer.

### Transformations Performed
- Removing duplicates
- Handling null values
- Standardizing formats
- Applying business rules
- Data validation

### Purpose
- Improve data quality
- Prepare datasets for analytics
- Create structured and reliable data

---

## Gold Layer – Business Ready Data

The Gold layer stores curated and aggregated datasets optimized for reporting and business analysis.

### Includes
- Fact tables
- Dimension tables
- KPIs and summary reports
- Analytical datasets

### Purpose
- Support dashboards and BI tools
- Enable business insights
- Improve decision-making

---

# Technologies Used

- SQL
- CSV Files
- Relational Database System
  - MySQL / PostgreSQL / SQL Server
- Medallion Architecture

---

# Project Workflow

1. Load raw CSV files into Bronze tables
2. Clean and transform data into Silver tables
3. Create business-ready Gold tables for analytics
4. Run SQL queries for reporting and insights

---

# Key Features

- Layered Medallion Architecture
- End-to-end ETL workflow using SQL
- CSV-based data ingestion
- Data cleaning and transformation
- Analytical data modeling
- Scalable warehouse design principles

---

# Purpose of the Project

This project is designed for learning and demonstrating:

- Data Warehousing concepts
- ETL pipeline development
- SQL transformation techniques
- Modern Medallion Architecture implementation
- Data engineering best practices

This repository serves as a beginner-friendly implementation of a modern data warehouse using structured CSV datasets and SQL-based processing.
