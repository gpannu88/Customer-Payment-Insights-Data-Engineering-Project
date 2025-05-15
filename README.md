# Customer Payment Insights Data Engineering Project

This project explores how data engineering and system design can be applied to a real-world business scenario involving customer credit accounts, transactional data, and proactive outreach. The solution includes both data transformation logic and a proposed system architecture for scaling and maintaining the pipeline in production.

## 📌 Project Overview

Many businesses offer 30-day credit accounts to their trade customers, enabling them to purchase supplies and pay at a later date. Staff working at branch or customer service levels often rely on experience and manual checks of transaction histories to assess whether customers may miss payment deadlines.

This project focuses on how data pipelines and supporting architecture can be used to:

- Systematically identify customers at risk of delayed payment
- Equip customer-facing teams with timely insights
- Enable scalable and repeatable analysis through automation

## 📂 Data Sources

The project uses simulated extracts from a production database, represented as CSV files:

- `accounts.csv` – Customer account information  
- `skus.csv` – Product details  
- `invoices.csv` – Invoices issued to accounts  
- `invoice_line_items.csv` – Itemized SKU data for each invoice  

These files are located in the `task_one/data_extracts` folder.

---

## 🛠️ Task One: ETL Pipeline Development

The first task involves building an ETL (Extract, Transform, Load) pipeline to prepare data for downstream analysis and machine learning models focused on late payment prediction.

### ✅ Deliverables

- A complete data transformation process from raw inputs to feature-rich output
- Tests that validate the pipeline using the provided CSV files
- Documentation of intermediate data models and rationale for their use
- An explanation of design decisions, including scalability considerations

📁 See the `task_one` directory for more details.

---

## 🧱 Task Two: System Architecture Design

The second task focuses on designing a robust, scalable system for operationalizing the ETL process in a production environment.

### ✅ Deliverables

- A proposed architecture for running and maintaining the ETL jobs
- An outline of how the system would evolve to support near real-time updates using Change Data Capture (CDC)
- Explanations of key architectural decisions and trade-offs

📁 See the `task_two` directory for more details.

---

## 💬 Summary

This project demonstrates practical data engineering and architectural thinking applied to a credit risk use case. Contributions, suggestions, and feedback are always welcome!
