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

**What is this project?**
- This project demonstrates a comprehensive data warehousing and analytics solution.
- From building a data warehouse to generating actionable insights.
- Designed as a poitfolio project, it highlights industry best-practices in data engineering and analytics.

**This project involves:**
- Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
- ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
- Data Modeling: Developing fact and dimension tables optimized for analytical queries.
- Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

---
---

## 🏗️🛢 Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

<img width="1174" height="872" alt="data_architecture" src="https://github.com/user-attachments/assets/9b239d78-dc16-4c89-85d2-9986458d8b8a" />  

Sources (.csv) → Bronze Layer (tables) → Silver Layer (tables) → Gold Layer (views) → Consumption (BI & Reporting, Ad-Hoc Querying , Machine Learning)  

- 📄 Sources: .csv files containing the raw data.  
- 🥉 Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.     
- 🥈 Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.     
- 🥇 Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
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

## 🚀 Project Requirements
#### Building the Data Warehouse (Data Engineering)
##### Objective
 Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications:
- Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
- Data Quality: Cleanse and resolve data quality issues prior to analysis.
- Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
- Scope: Focus on the latest dataset only; historization of data is not required.
- Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

----

#### BI: Analytics & Reporting (Data Analysis)
Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

---

## © Licence

This project is licensed under the [MIT License](https://github.com/charlespughtech/sql-data-warehouse-project/blob/main/LICENSE). You are free to use, modify, and share this project with proper attribution.

---

## 📩 Contact

**For any enquiries or further information, please contact**:

**Charles Pugh** - Google-certified Data Analyst  
**Website:** [https://charlespughtech.github.io/](https://charlespughtech.github.io/)  
**Email:** [charlespughtech@gmail.com](mailto:charlespughtech@gmail.com)  
**LinkedIn:** [https://www.linkedin.com/in/charlespughtech/](https://www.linkedin.com/in/charlespughtech/)

---
