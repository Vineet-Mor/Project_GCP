# Project_GCP
The project aims to build an end-to-end ETL pipeline on Google Cloud Platform (GCP) to extract data from various sources, transform it into a usable format, and load it into a data warehouse or data lake. The pipeline will provide clean, reliable data to data analysts and data scientists for analysis and model training purposes.

1. Project Description: 
   - Building an ETL pipeline to extract data from various sources, transform it into usable format, and load it into data warehouse for data analysis.
   - Stakeholders: Data Engineers, Data analysts, Data Scientists, Project Managers.
2. Data Sources:
   - On premise data
   - Cloud Storage
   - Amazon cloud

3. Data Extraction:
   - Utilized Google cloud services such as Cloud Storage, Bigquery for data extraction from google cloud storage buckets.
   - Implemented scheduled batch jobs to ingest data into Google Cloud environment.
     
4. Data Transformation:
   - Extracted data goes under data transformation using Dataproc to clean, enrich and prepare for analysis.
   - Implement data quality checks and error handling mechanisms.

5. Data Loading:
    - Loaded transformed data into target data warehouse (BigQuery) for analytics and data lake (Google Cloud Storage).

6. Data governance and Security:
   - Implement access controls and encryption mechanisms to ensure data security and compliance.
   - Establish data lineage and metadata management processes using DAG.

