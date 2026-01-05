# databricks-level1-retail-analytics
Retail sales analytics using Databricks, Spark, and Delta Lake

### Data Layers
- **Raw Layer**: Original ingested data
- **Clean Layer**: Filtered and validated data

---

## Dataset

**Online Retail Dataset**
- Format: CSV
- Source: Public retail transaction dataset
- Key Columns:
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - Country

---

## Technologies Used
- Databricks Community Edition
- Apache Spark (PySpark)
- Delta Lake
- Unity Catalog (UC-first design)
- SQL

---

## Data Processing Steps
1. Uploaded raw CSV data to Databricks
2. Ingested data using Spark DataFrame API
3. Cleaned invalid records (negative quantity, price)
4. Converted invoice date to timestamp
5. Stored data as Delta tables using Unity Catalog
6. Ran analytical SQL queries

---

## Sample Analytics
- Total sales by country
- Top selling products
- Delta table version history

---

## Key Learnings
- Hands-on experience with Databricks notebooks
- Practical Spark DataFrame usage
- Delta Lake fundamentals (ACID, versioning)
- Unity Catalog table organization
- SQL analytics on Delta tables

---

## Next Steps
- Automate ingestion using Databricks Workflows
- Add parameterized pipelines
- Implement Delta time travel recovery
- Extend project to Level 2 (Automation)

---

## 📎 Notebook
The Databricks notebook is available in the `notebook/` folder.

