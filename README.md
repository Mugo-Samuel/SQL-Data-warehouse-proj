SQL DATA WAREHOUSE PROJECT
Welcome 
Data Warehouse Project – Modern Medallion Architecture
Overview

This project demonstrates the development of a modern data warehouse using the Medallion Architecture (Bronze, Silver, Gold layers) to transform raw data into analytics-ready datasets.

The goal of the project is to design a scalable pipeline that ingests raw data, cleans and transforms it, and delivers structured datasets that support business intelligence and decision-making.

Architecture

The warehouse follows the Medallion Architecture approach:

Bronze Layer

Stores raw data ingested from source systems

Data is loaded without transformations

Preserves the original structure for traceability

Silver Layer

Data cleaning and transformation

Standardization of formats and data types

Removal of duplicates and invalid records

Gold Layer

Business-level datasets

Aggregated and analytics-ready tables

Used for reporting and dashboarding

Data Pipeline Workflow

Extract raw datasets from source systems

Load data into the Bronze layer

Transform and clean data in the Silver layer

Build dimensional models and aggregated tables in the Gold layer

Use the final datasets for analytics and reporting

Technologies Used

SQL Server

SQL

Draw.io – Data architecture design

Git & GitHub – Version control

Data Warehouse Modeling

Data Modeling

The Gold layer uses dimensional modeling techniques, including:

Fact tables for measurable events

Dimension tables for descriptive attributes

Optimized schema design for analytical queries

Key Features

End-to-end data warehouse pipeline

Structured Medallion Architecture

Data cleaning and validation

Dimensional modeling for analytics

Scalable design for BI tools

Project Structure
data-warehouse-project
│
├── bronze_layer
│   └── raw data ingestion scripts
│
├── silver_layer
│   └── data cleaning and transformation
│
├── gold_layer
│   └── analytics and dimensional models
│
├── architecture
│   └── data warehouse architecture diagram
│
└── README.md
Example Use Cases

Sales performance analysis

Customer behavior analysis

Business performance reporting

Data-driven decision making

Future Improvements

Integration with BI tools such as Power BI

Automated ETL pipelines

Real-time data processing

Author

Samuel Mugo
