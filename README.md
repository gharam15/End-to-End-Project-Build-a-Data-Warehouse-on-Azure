# End-to-End-Project-Build-a-Data-Warehouse-on-Azure for Trip Analytics 

This project aims to build a scalable data warehouse architecture using Azure services to analyze Trip usage data.

##  Technologies Used

- Azure Data Lake Gen2
- Azure Synapse Analytics
- Azure Data Factory
- PostgreSQL (Azure Database for PostgreSQL)
- Python (Pandas, psycopg2)
- Power BI

## Project Steps

1. Collect and upload raw CSV files to Azure Data Lake
2. Transform and clean the data using Python
3. Load the data into PostgreSQL using a custom Python script
4. Connect Azure Synapse to PostgreSQL for large-scale querying
5. Build a Power BI dashboard to visualize key bike usage metrics

## ⚙ How to Run

```bash
python ProjectDataToPostgres.py
