SQL DATA WAREHOUSE PROJECT
Welcome 
# Data Warehouse Project – Modern Medallion Architecture

## Overview
This project demonstrates the development of a modern data warehouse using the Medallion Architecture (Bronze, Silver, Gold layers) to transform raw data into analytics-ready datasets. The goal is to build a scalable pipeline that ingests raw data, cleans and transforms it, and produces structured datasets for business intelligence and analytics.

## Architecture
The project follows the Medallion Architecture approach:

Bronze Layer
- Stores raw data from source systems
- Data is ingested with minimal or no transformation
- Maintains original data for traceability

Silver Layer
- Performs data cleaning and transformation
- Standardizes formats and data types
- Removes duplicates and invalid records

Gold Layer
- Contains business-level datasets
- Includes aggregated and analytics-ready tables
- Optimized for reporting and analysis

## Data Pipeline Workflow
1. Extract data from source systems
2. Load raw data into the Bronze layer
3. Clean and transform data in the Silver layer
4. Build dimensional models and analytics tables in the Gold layer
5. Use the final datasets for reporting and analytics

## Technologies Used
- SQL Server
- SQL
- Draw.io (for data architecture design)
- Git & GitHub

## Data Modeling
The Gold layer uses dimensional modeling techniques including:
- Fact tables for measurable business events
- Dimension tables for descriptive attributes
- Optimized schema for analytical queries

## Key Features
- End-to-end data warehouse pipeline
- Structured Medallion Architecture
- Data cleaning and validation
- Dimensional modeling for analytics
- Scalable warehouse design

## Project Structure
data-warehouse-project
│
├── bronze_layer
├── silver_layer
├── gold_layer
├── architecture
└── README.md

## Use Cases
- Sales performance analysis
- Customer behavior analysis
- Business performance reporting
- Data-driven decision making

## Author
Samuel Mugo
