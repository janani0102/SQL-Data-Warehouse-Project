# SQL-Data-Warehouse-Project
Building a modern data warehouse with SQL server including ETL processes, Data modeling and Analytics.

## 📖 Project Overview
This project covers:

1. **Data Architecture** – Designing a modern data warehouse using Bronze, Silver, and Gold layers.
2. **ETL Pipelines** – Extracting, transforming, and loading data from source systems.
3. **Data Modeling** – Creating fact and dimension tables for analytical queries.
4. **Analytics & Reporting** – Using SQL to generate insights on customer behavior, product performance, and sales trends.

---

## 🏗️ Data Architecture
The project follows the **Medallion Architecture** with three layers: **Bronze, Silver, and Gold**.

1. **Bronze Layer** – Stores raw data as-is from the source systems. Data is loaded from CSV files into SQL Server.
2. **Silver Layer** – Cleans, standardizes, and transforms the raw data to prepare it for analysis.
3. **Gold Layer** – Contains business-ready data modeled using a **star schema** for reporting and analytics.

---

## 🛠️ Tools

* **SQL Server Express** – Database
* **SSMS** – SQL development and database management
* **SQL** – ETL, transformation, and analytics
* **GitHub** – Version control and project management
* **Draw.io** – Architecture and data modeling
* **Notion** – Project planning and documentation

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Project documentation
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── naming-conventions.md
│
├── scripts/                            # SQL scripts
│   ├── bronze/                         # Raw data loading
│   ├── silver/                         # Data cleaning and transformation
│   └── gold/                           # Analytical models
│
├── tests/                              # Data quality tests
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt

