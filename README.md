# SQL Data Warehouse Project

## Overview
This project demonstrates the implementation of a modern Data Warehouse using the Medallion Architecture approach with Bronze, Silver, and Gold layers.

The project focuses on:
- Data ingestion
- Data cleaning and transformation
- Data modeling
- ETL workflows
- Analytical reporting using SQL

---

# Architecture

This project follows the Medallion Architecture pattern:

## Bronze Layer
The Bronze layer stores raw ingested data from source systems.

### Purpose
- Preserve original data
- Enable traceability
- Support reprocessing

### Operations
- Raw data loading
- Minimal transformation
- Data ingestion from source files/tables

---

## Silver Layer
The Silver layer contains cleaned and transformed data.

### Purpose
- Improve data quality
- Standardize formats
- Remove duplicates and null issues

### Operations
- Data cleansing
- Data validation
- Data transformation
- Business rule implementation

---

## Gold Layer
The Gold layer contains business-ready analytical data.

### Purpose
- Reporting
- Dashboarding
- Business analytics
- machine learning






---

