# Data-Warehouse-CRM-and-ERP-Data-Integration-for-Business-Insights


This project showcases the design and implementation of a **Modern Data Warehouse** using **SQL Server**, following the **Medallion Architecture** (Bronze → Silver → Gold). It integrates data from **CRM and ERP systems**, preparing it for analytical reporting and business insights.

---

## 🏗️ Data Architecture
![Project Architecture](https://github.com/Navyam-04/Data-Warehouse-CRM-and-ERP-Data-Integration-for-Business-Insights/blob/main/documents/project_architecture.png?raw=true)

The architecture adopts the **Medallion Layered Approach**:

- 🔹 **Bronze Layer**: Raw data ingested from CSV files (CRM & ERP sources) into SQL Server.
- 🔸 **Silver Layer**: Cleansed, transformed, and normalized data ready for modeling.
- 🏆 **Gold Layer**: Business-ready data modeled into a **Star Schema** for efficient reporting.

---

## 📌 Project Overview

This project involves:

- ✅ **Data Architecture**: Design using Bronze, Silver, and Gold layers.
- 🔄 **ETL Pipelines**: SQL scripts for Extract, Transform, and Load operations.
- 📦 **Data Modeling**: Fact and dimension tables optimized for analytics.
- 📈 **Analytics & Reporting**: SQL-based insights for decision-making.

---


---

## 🚀 Project Requirements

### 💻 Data Engineering (ETL)

- Integrate ERP & CRM datasets from CSV files
- Resolve data quality issues
- Combine datasets into a unified model
- Use SQL Server for database and processing
- Document all SQL in organized scripts

### 📊 Data Analytics

- Analyze customer behavior, sales trends, product performance
- Enable decision-making via clean, accessible datasets

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/               # Raw CRM & ERP CSV files
├── docs/                   # Architecture, models, diagrams
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
│   └── data_catalog.md
│
├── scripts/
│   ├── bronze/             # Load raw data
│   ├── silver/             # Clean and transform
│   └── gold/               # Star schema modeling
│
├── tests/                  # Test scripts and QA queries
├── README.md               # This file
├── LICENSE                 # MIT License
├── .gitignore              # Git ignore rules
└── requirements.txt        # Optional dependencies
```

---

## 🧰 Tools Used

- 📄 SQL Server Express + SSMS
- 📁 CSV (CRM and ERP Data)
- 🧮 SQL for all ETL and modeling
- 📝 DrawIO for diagrams

---







## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share this work with proper attribution.

---
## 🔗 Connect with Me  
👋 Hi, I'm **Mangali Navya**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/navya-mangali/)  
[![Email](https://img.shields.io/badge/Email-Send%20Mail-red?logo=gmail)](mailto:middenavya51@gmail.com)  
[![GitHub](https://img.shields.io/badge/GitHub-Navyam--04-black?logo=github)](https://github.com/Navyam-04)  
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-purple?logo=internet-explorer)](https://mangalinavya.my.canva.site)


_"Learn deeply. Build boldly. Share generously."_

