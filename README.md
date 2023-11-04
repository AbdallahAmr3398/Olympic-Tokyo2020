# Olympic-Tokyo2021
Overview
This project involved the analysis of Olympic data related to the Tokyo Olympics 2020 using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, Azure Databricks, and Power BI. The goal was to extract, transform, load, and analyze Olympic data to gain insights and create informative dashboards and reports.

Project Steps
1. Data Collection and Preparation
A storage account was created, including a container containing two files, one of which served as the data file. The data was loaded into Data Lake Gen 2.
Data was integrated from GitHub, comprising five Excel files through Azure Data Factory using data pipelines.
2. Data Pipeline Creation (Data Factory)
Data Factory was used to create data pipelines for ETL processes.
Data was extracted from various sources, transformed, and loaded into the Data Lake.
3. Data Transformation (Azure Databricks)
Data transformation and cleaning were performed using PySpark within Azure Databricks.
4. Data Analysis and Loading (Synapse Analytics)
The transformed data was analyzed using SQL queries and other analytics within Azure Synapse Analytics.
The insights gained from the analysis were used to load data for further processing and visualization.
5. Dashboard and Report Creation (Power BI)
A dashboard and report were created using Power BI to visualize and communicate the findings from the Tokyo Olympics 2020 data.
How to Replicate the Project
To replicate this project, follow these steps:

Create a storage account and container for your data.
Integrate data from the desired sources using Azure Data Factory.
Build data pipelines to transform and load the data into Azure Data Lake Gen 2.
Use Azure Databricks with PySpark for data transformation.
Analyze the transformed data using Azure Synapse Analytics.
Create reports and dashboards with Power BI to present the data insights.
Author
[Abdallah Amr]
