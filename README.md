# 🛠️ Data Warehouse Project – Medallion Architecture

This project implements a  data warehouse using the **Medallion Architecture**, structured in three layers: **Bronze**, **Silver**, and **Gold**. It demonstrates a complete ETL pipeline to ingest, transform, and curate data for analytics and reporting.

---

## 📐 Architecture Overview

Source Data → 🟫 Bronze Layer → 🟪 Silver Layer → 🟨 Gold Layer → 📊 Analytics
- **Bronze**: Raw data ingestion with minimal processing
- **Silver**: Cleaned and structured data with applied transformations
- **Gold**: Curated, aggregated datasets for business reporting and analysis


## 🔁 ETL Flow

1. **Bronze Layer**:  
   - Ingested raw CSV/JSON files from source systems.
   - Stored in the `bronze.crm_cust_info`, `bronze.crm_sales_details`, etc.

2. **Silver Layer**:  
   - Applied filtering, joins, and data normalization.
   - Created refined tables.

3. **Gold Layer**:  
   - Business-level aggregations, KPIs, and denormalized views.

## 🙏 Credits

Inspired by [Data With Baraa](https://www.youtube.com/@DataWithBaraa).

