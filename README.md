# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project that highlights industry's best practices in data engineering and analytcis.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) providede as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trend**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

### Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver and Gold layers:

<img width="1082" height="800" alt="Data Architecture" src="https://github.com/user-attachments/assets/0cff7b33-f552-47a2-b950-8113b0976701" />

1. **Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server Database.
2. **Silver Layer:** This layer includes data cleaning, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 🔗 License

This project is licensed under the [MIT License]. You are free to use, modify, and share this project with proper attributoin.

## About me

Hi there! I am **Harsh Pipalia**. I'am an graduate student at Lehigh University, aspiring to become a Data Engineer.
