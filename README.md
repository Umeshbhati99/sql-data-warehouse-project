# Data Warehouse Project

Welcome to the **Data Warehouse Project** repository!
This Project demonstrates a comprehensive data warehousing, from building a data warehouse to prepare data for generating actionable insights, Designed as a portfolio project highlights industry best practices in data engineering.

...

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## Project Requirements

### Building the Data Warehouse (Data Engineering)

### Objectives
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision making.

### Specifications
**Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.

**Data Quality**: Cleanse and resolve data quality issues prior to analysis.

**Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.

**Scope**: Focus on the latest dataset only; historization of data is not required.

**Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

...

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

## License

This project is licensed under the [MIT License] (LICENSE).

## About Me

Hi there! I'm **Umesh Bhati**, A Self-taught Data Engineer.
