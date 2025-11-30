# SQL Data Warehouse Project 📊

## ⚙️ Overview  
This project demonstrates a full end-to-end Data Warehouse solution built using SQL Server. It follows the **Medallion Architecture** (Bronze → Silver → Gold) and ends with a clean star-schema ready for analytics and reporting.  

The goal is to consolidate data from CRM and ERP sources, clean and normalize it, and build a structured warehouse that supports reporting, business-insights and analytics.

---

## 🧩 Project Structure  
/datasets/ # Raw source data (CSV files from CRM and ERP)
/docs/ # Documentation: data catalog, architecture diagrams, data flows, models, etc.
/scripts/ # ETL / transformation SQL scripts (bronze → silver → gold)
/tests/ # Any test scripts or sample queries
README.md # This file


---

## 🚀 What this project includes  

- Data ingestion of raw CRM & ERP data into “Bronze” tables.  
- Data cleansing, normalization and standardization in the Silver layer.  
- Building the “Gold” layer: dimension and fact views/tables (star schema) — e.g. customers, products, sales fact.  
- Documentation of data model, naming conventions, data flows, and schema design.  
- Designed with best practices so that the final data model is ready for analytics / BI / reporting tools (Power BI / Tableau / SQL queries).  

---

## 📦 Prerequisites & Tools  

- SQL Server (any edition — SQL Server Express works)  
- SQL Server Management Studio (SSMS) or any SQL client  
- Git + GitHub to manage version control  
- (Optional) Diagram tools such as Draw.io for reviewing architecture & data models  

---

## 📝 How to Use  

1. Clone the repo:  
   ```bash
   git clone https://github.com/Ahmed010622/Sql_DataWarehouse_Project.git
2. Load the CSV files from /datasets/ into the Bronze tables (raw tables).
3. Run the SQL scripts in /scripts/ to transform data through Silver then Gold layers.

4. Explore the resulting views (dimensions and facts).

5. Use these views in your BI tool or SQL queries for analytics and reporting.

