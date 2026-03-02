# Finance Data Engineering Pipeline | Azure & Databricks

## 📊 Project Overview

This project demonstrates an end-to-end Finance Data Engineering pipeline built using Azure cloud services and Databricks.

The solution follows the Medallion Architecture (Bronze, Silver, Gold) to process financial transaction data and generate business KPI reports.
Data set processed here is approximately 1.5-2 GB.

---

## 🏗️ Architecture

The pipeline is built using:

- Microsoft Azure
- Azure Data Lake Storage Gen2
- Azure Databricks
- PySpark
- Delta Lake
- SQL

Data Flow:

Raw CSV Files
     ↓
Azure Data Lake (Raw Layer)
     ↓
Azure Databricks (Bronze Layer - Raw Ingestion)
     ↓
Delta Tables (Silver Layer - Cleaned Data)
     ↓
Aggregated Data (Gold Layer - Business Insights)
     ↓
Databricks Dashboard
---

## 📁 Project Structure

```
finance-data-engineering-project/
│
├── 01_ingestion_bronze_layer
├── 02_transformation_silver_layer
├── 03_aggregation_gold_layer
├── 04_dashboard/
├── finance-sample-data-sets
└── README.md
```

---

## 📌 Key Business Reports Generated

- High value accounts (> $1B)
- France customer analysis
- Unique country distribution
- High value transactions (> $2000)
- Highest loan issued
- Top 5 business loans
- Lowest balance customers
- Interest rate analysis
- Most frequent ledger type
- Pending transaction count

---

## 🛠️ Technologies Used

- PySpark
- Delta Lake
- Azure Data Lake Storage Gen2
- Azure Databricks
- SQL

---

## 💡 Skills Demonstrated

- Data ingestion using PySpark
- Medallion architecture implementation
- Delta Lake table creation
- Data transformation & cleaning
- Aggregations & business KPI generation
- Cloud storage integration
- End-to-end data pipeline design

---

## 🔐 Security Note

All storage access keys and credentials have been removed before publishing this project.

---

## 👨‍💻 Author

Harshul  
Aspiring Data Engineer