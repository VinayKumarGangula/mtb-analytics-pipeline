# 🏦 M&T Bank – Automated Financial Analytics Pipeline

This project showcases a production-level financial analytics solution designed for M&T Bank. The goal was to streamline reporting workflows, reduce data latency, and enhance decision-making using a fully automated ETL pipeline integrated with AWS services and Power BI.

---

## 🧠 Project Overview

During my role as a Data Analyst at M&T Bank, I led the development of an end-to-end analytics pipeline that automated financial data extraction, transformation, validation, and visualization. The system ingests data from transactional sources, processes it through AWS Glue jobs, and loads it into Amazon Redshift for downstream analytics and Power BI dashboards.

This solution eliminated repetitive manual processes, reduced reporting delays by 40%, and improved executive data access with validated KPIs.

---

## 🔧 Tools & Technologies Used

- **AWS Glue** – ETL job orchestration
- **AWS Lambda** – Workflow triggers and alerting
- **Amazon Redshift** – Central data warehouse
- **Python** – Data cleaning, validation, automation scripts
- **SQL** – Data modeling, transformation, and aggregation
- **Power BI / Tableau** – Executive dashboards and financial reporting

---

## 🔂 Workflow Overview

1. **Ingest**  
   - Raw financial and transactional data is collected from upstream systems.

2. **ETL Processing**  
   - AWS Glue jobs clean and standardize datasets (e.g., invoices, transactions, budget logs).
   - Python scripts perform QA checks, anomaly detection, and schema validation.

3. **Storage**  
   - Cleaned data is stored in Amazon Redshift tables with partitioning for performance.

4. **Reporting**  
   - Power BI dashboards connect to Redshift to visualize financial KPIs:
     - Revenue, Net Margin, Expense Ratios, Variance Analysis
     - Forecasts vs Actuals
     - Alert systems for anomalies

---

## 🧩 Folder Structure


---

## 🚀 How to Use

> 📌 Files will be uploaded soon

Once available:
1. Review Python scripts under `/etl` for transformation logic
2. Use `schema.sql` to deploy tables in Redshift
3. Download `.pbix` files and open in Power BI Desktop
4. Connect dashboards to Redshift or sample dataset for testing

---

## 🎯 Project Impact

- ⏱️ Reduced report generation time by **40%**
- 📊 Improved decision turnaround through **validated KPIs**
- ✅ Reduced reconciliation errors by **40%** using Python-based QA
- 🧠 Increased executive engagement by delivering visual insights across financial data

---

## 📬 Contact

vinayreddygangula8@gmail.com  
[LinkedIn](https://linkedin.com/in/vinay-kumar-gangula-2b78871a7)
