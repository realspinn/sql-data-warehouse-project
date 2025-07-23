# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository!
This project demonstrates a comprehensive end-to-end data warehousing and analytics solution—from building a scalable warehouse to delivering business-ready insights. Designed as a portfolio project, it highlights industry best practices in **data engineering, ETL, data modeling, and analytics**.

---

## Data Architecture

This project follows the **Medallion Architecture** (Bronze, Silver, Gold layers):

- **Bronze Layer**: Stores raw data from ERP and CRM CSV files, loaded into a SQL Server database.
- **Silver Layer**: Cleanses, standardizes, and prepares the data for analysis.
- **Gold Layer**: Hosts the star schema with business-ready data for analytics and reporting.

---

## Project Overview

This project involves:

- **Modern Data Architecture** using SQL Server and Medallion layers.
- **ETL Pipelines** to extract, transform, and load data from source files.
- **Data Modeling** using star schema for performance and clarity.
- **SQL-based Reporting & Analytics** to extract meaningful business insights.

---

## Ideal For

This repository is an excellent reference for anyone looking to showcase skills in:

- SQL Development  
- Data Engineering  
- Data Warehousing  
- ETL Pipeline Development  
- Data Modeling  
- Analytics and Business Intelligence  

---

## Tools & Resources (Free)

- **Datasets**: ERP & CRM data (CSV)
- **SQL Server Express**: Lightweight SQL database server
- **SSMS** (SQL Server Management Studio): GUI for managing SQL Server
- **GitHub**: For code collaboration and version control

---

## Project Requirements

### Data Engineering Phase
- **Data Sources**: Ingest two datasets (ERP & CRM)
- **Data Quality**: Clean and prepare data
- **Integration**: Merge sources into a unified model
- **Modeling**: Create fact and dimension tables
- **Scope**: Focused on current data only (no historization)
- **Docs**: Provide clear documentation for the model

### Analytics Phase
- **Objective**: Use SQL to deliver insights around:
  - Customer behavior  
  - Product performance  
  - Sales trends  

More details in `docs/requirements.md`.

---

##  Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── HL.draw.io        # Draw.io file shows the project's architecture
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
```

---

## License

This project is licensed under the [MIT License](LICENSE). You can freely use, modify, and distribute it with proper attribution.

---

## About Me

Hi there! I’m **Israel Adeleye**, also known as **Realspinn** a passionate and resilient self-taught database developer.

Despite not studying a tech-related course, I’m committed to mastering data engineering, SQL, and database architecture through hands-on projects like this. I believe in learning by doing and building things that matter.

Currently exploring:
- Modern data warehouse designs  
- SQL performance optimization  
- Real-world ETL workflows  
- End-to-end analytics pipelines  

Let’s connect and build something impactful together!

---


