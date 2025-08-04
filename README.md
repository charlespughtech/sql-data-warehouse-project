# 🏭 SQL Server Data Warehouse Project 
#### Building a modern data warehouse with SQL Server, including ETL processes, data modelling and analytics.

---

#### Project Repository URL: [charlespughtech/sql-data-warehouse-project](https://github.com/charlespughtech/sql-data-warehouse-project) 

---

**Author:** Charles Pugh - Google-certified Data Analyst   
**Website:** [https://charlespughtech.github.io/](https://charlespughtech.github.io/)  
**Email:** [charlespughtech@gmail.com](mailto:charlespughtech@gmail.com)  
**LinkedIn:** [https://www.linkedin.com/in/charlespughtech/](https://www.linkedin.com/in/charlespughtech/)  
**Date:** 2025-07-26

---

Welcome to my **Data Warehouse and Analytics Project** repository!   

## 📖 Project Overview

**This project involves:**
- 🏗️ Data Architecture: Designing a modern data warehouse using a medallion architecture: bronze, silver, and gold layers. The bronze layer contains unchanged data tables from the csv files, the silver layer contains cleansed and standardised data also in table form, the gold layer contains business ready data in the form of VIEWs.

- 🔄 ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse. I utilised stored procedures for the ETL process to ensure that a small amount of code could be run to Extract, Transform and Load the data from raw csv files right up to the gold layer. This ensures ease, accuracy and speed of ETL processing.

- 📚 Data Integration: Using JOINs, data cleansing and data integration techniques to combine relevant datasets into easier to singular datasets.

- 🧹 Data Cleansing:
Handling NULLs, standardisation/normalisation, utilising TRIM to remove whitespace, using CASE WHEN statements to standardise data.

- 🗃️ Data Modeling: Utilised a star schema for developing fact and dimension tables optimized for analytical queries. The dimension tables include customer and product details, the fact table includes sales order data.

- 🗺 Data Catalogue: The data catalogue can be used to help navigate the data warehouse. It enables end-user understanding of the structure, relationships and types of data.

---

## 🛢 Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

<img width="1174" height="872" alt="data_architecture" src="https://github.com/user-attachments/assets/9b239d78-dc16-4c89-85d2-9986458d8b8a" />  

Sources (.csv) → Bronze Layer (tables) → Silver Layer (tables) → Gold Layer (views) → Consumption (BI & Reporting, Ad-Hoc Querying , Machine Learning)  

- 📄 Sources: .csv files containing the raw data.  
- 🥉 Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.     
- 🥈 Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.     
- 🥇 Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 🛠️ Important Links & Tools (Free):
- [**Datasets**](https://github.com/charlespughtech/sql-data-warehouse-project/tree/main/datasets): Access to the project dataset (csv files).
- [**SQL Server Express**](https://www.microsoft.com/en-us/sql-server/sql-server-downloads): Lightweight server for hosting your SQL database.
- [**SQL Server Management Studio (SSMS)**](https://learn.microsoft.com/en-us/ssms/install/install?view=sql-server-ver16): GUI for managing and interacting with databases.
- [**Git Repository**](https://github.com): Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- [**DrawIO**](https://www.drawio.com/): Design data architecture, models, flows, and diagrams.
- [**Notion**](https://www.notion.com/): Get the Project Template from Notion
- [**Notion Project Steps**](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269): Access to All Project Phases and Tasks.

---

## 📋 Project Requirements
**This project:**
[charlespughtech/sql_data_warehouse_project](https://github.com/charlespughtech/sql_data_warehouse_project)
### Building the Data Warehouse (Data Engineering)
#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications:
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.


**The follow-up project:** 

[https://github.com/charlespughtech/sql_exploratory_data_analysis_project](https://github.com/charlespughtech/sql_exploratory_data_analysis_project)
### BI: Analytics & Reporting (Data Analysis)
#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---
## 🗃️ Repository Structure

```bash
sql-data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.png                         # png file shows all different techniquies and methods of ETL
│   ├── Project_Notes_Sketcghes.pdf     # .pdf file containing project notes & sketches
│   ├── data_architecture.png           # .png file shows the project's architecture
│   ├── data_catalogue.md               # .md file containing a catalogue of datasets, including field descriptions and metadata
│   ├── data_flow.png                   # .png file for the data flow diagram
│   ├── data_integration.png            # .png file shows the relationships between the tables
│   ├── data_layers.pdf                 # .pdf file for the data layers
│   ├── data_model.png                  # .png file for data model (star schema)
│   └── naming_conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   └── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
└── .gitignore                          # Files and directories to be ignored by Git
```

---

## © Licence

This project is licensed under the [MIT License](https://github.com/charlespughtech/sql-data-warehouse-project/blob/main/LICENSE). You are free to use, modify, and share this project with proper attribution.

---

🤝🏻 Credit to [DataWithBaraa](https://github.com/DataWithBaraa) for helping me to create this project and enabling me to develop my skillset.

---

## 📩 Contact

**For any enquiries or further information, please contact**:

**Charles Pugh** - Google-certified Data Analyst  
**Website:** [https://charlespughtech.github.io/](https://charlespughtech.github.io/)  
**Email:** [charlespughtech@gmail.com](mailto:charlespughtech@gmail.com)  
**LinkedIn:** [https://www.linkedin.com/in/charlespughtech/](https://www.linkedin.com/in/charlespughtech/)

---
