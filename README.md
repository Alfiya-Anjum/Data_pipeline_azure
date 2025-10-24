# Data_pipeline_azure

## Project Overview

This project demonstrates an end-to-end data engineering pipeline built entirely on Microsoft Azure.
It covers the complete data lifecycle — ingestion, storage, transformation, and reporting — using powerful Azure services.

## Architecture Diagram

![IMG-20251024-WA0021(1)](https://github.com/user-attachments/assets/7c3aeb2b-e34f-495c-9e1d-1d8bdbc1ddf9)



## Tech Stack

Azure Data Factory – for orchestrating and automating data ingestion

Azure Data Lake Gen2 – for scalable and secure data storage

Azure Databricks (Apache Spark) – for data transformation and processing

Azure Synapse Analytics – for serving and querying data efficiently

Power BI – for data visualization and reporting

## Data Flow

Data Source: Data is extracted from an HTTP source.

Data Ingestion (ADF): Azure Data Factory pipelines load raw data into Data Lake Gen2.

Data Transformation (Databricks): Using Apache Spark notebooks, data is cleaned, transformed, and enriched.

Serving (Synapse Analytics): The transformed data is loaded into Synapse for analytical queries.

Reporting (Power BI): Final dashboards are created to visualize business insights.

**Data Pipeline in Azure Data Factory**

<img width="1807" height="759" alt="Screenshot 2025-10-25 000436" src="https://github.com/user-attachments/assets/e46658d8-cb87-437a-847a-fc4710a04537" />


** Data Transformation in Databricks**

https://github.com/Alfiya-Anjum/Data_pipeline_azure/blob/main/SILVER_LAYER.ipynb

**Power BI Dashboard**

<img width="1207" height="679" alt="Screenshot 2025-10-24 224731" src="https://github.com/user-attachments/assets/6c453c4b-0700-4b2a-a8e3-c2ff48d8dd42" />


## What I Learned

Designing and implementing a robust data pipeline using Azure Data Factory

Handling data integration and transformation using Databricks + Apache Spark

Using Azure Synapse Analytics for efficient data warehousing and analytics

Applying best practices for big data and real-time processing

Understanding Azure Data Engineer interview concepts through hands-on experience

## Future Improvements

Add CI/CD pipeline for automation using GitHub Actions or Azure DevOps

Integrate real-time data streaming with Azure Event Hubs or Kafka

Add monitoring and alerting using Azure Monitor


