# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture: Bronze, Silver, and Gold layers.

![Data Architecture](docs/data_architecture.png)

**Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server Database.

**Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

**Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 📖 Project Overview

This project involves:

- **Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture (Bronze, Silver, and Gold layers).
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

## 🛠️ Important Links & Tools

Everything used in this project is free!

- **Datasets:** Access to the project dataset (CSV files).
- **SQL Server Express:** Lightweight server for hosting your SQL database.
- **SQL Server Management Studio (SSMS):** GUI for managing and interacting with databases.
- **Git Repository:** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **Draw.io:** Design data architecture, models, flows, and diagrams.
- **Notion:** All-in-one tool for project management and organization.
- **Notion Project Steps:** Access to all project phases and tasks.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**

- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

**Objective**

Develop SQL-based analytics to deliver detailed insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to `docs/requirements.md`.

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing ETL techniques and methods
│   ├── data_architecture.drawio        # Project architecture
│   ├── data_catalog.md                 # Dataset catalog, field descriptions and metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Data models (star schema)
│   ├── naming-conventions.md           # Naming guidelines for tables, columns and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                          # Scripts for cleaning and transforming data
│   ├── gold/                            # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements
```

---

## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

Hi there! I'm **Shahil Ahmed MF**, a BCA graduate (2025) from Bengaluru, India, passionate about Data Analytics, Data Science, and Artificial Intelligence.

I'm continuously developing my technical skills and building hands-on projects using SQL, Python, Power BI, and Machine Learning. My goal is to leverage data to solve real-world problems and generate meaningful business insights.

I'm always eager to learn, explore new technologies, and connect with people in the data and AI community.

### Let's Connect!

- **GitHub:** [shaz-code](https://github.com/shaz-code)

⭐ If you find this project useful, feel free to explore and connect!
```
