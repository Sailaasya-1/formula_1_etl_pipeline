# ☁️ End-to-End Azure Data Engineering Pipeline



### 📌 Overview

This project implements an end-to-end data pipeline using Databricks (PySpark) to process data from 8 source tables stored in Azure Data Lake Storage (ADLS).
Azure Data Factory (ADF) orchestrates the workflow by triggering Databricks notebooks in sequence.


### Architecture

- Azure Data Factory – Orchestrates and schedules notebook execution
- Databricks (PySpark) – Performs ingestion, cleaning, and transformations
- Azure Data Lake Storage – Stores raw and processed data

### Data Flow (https://www.kaggle.com/datasets/jtrotman/formula-1-race-data)

- ADF triggers Databricks notebooks.
- Databricks reads raw data from ADLS.
- PySpark applies validation and transformations.
- Processed datasets are written back to ADLS for analysis.


### 🔹Technologies 

- Azure Data Factory
- Azure Data Lake Storage
- Databricks
- PySpark

  
