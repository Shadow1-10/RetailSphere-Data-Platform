# RetailSphere Data Platform

## Overview
RetailSphere is an end-to-end data engineering project implementing a modern data warehouse pipeline.

## Architecture

Raw Data
   ↓
Bronze Layer
   ↓
Silver Layer
   ↓
Gold Layer
   ↓
Analytics Dashboard


## Tech Stack

- Python
- PySpark
- SQL
- Databricks
- Cloud Storage
- Delta Lake
- Power BI


## Data Model

Star schema consisting of:

Fact Tables:
- fact_sales

Dimension Tables:
- dim_customer
- dim_product
- dim_store
- dim_date
