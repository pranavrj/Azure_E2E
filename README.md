## Azure End to End Data Engineering

Project Architecture:

![Architecture](https://github.com/pranavrj/Azure_E2E/assets/25327428/d27c9982-1cef-4d96-a218-fc99059b2e8b)

Project Overview: 

1) Migrate on Prem data into Azure cloud using ADF.
2) Transform the data in ADLS into Gold layer format using PySpark within Azure Databricks.
3) Copied the data into Azure synapse to run further analysis using SQL.
4) Linked the data within Azure Synapse with Power BI for reporting.

In this project I have migrated 19 tables from MS-SQL Sever (locally hosted) into Azure Data lake using Azure data factory. An ADF pipeline with a parameterized dataset and self hosted IR was setup to copy the data into Azure storage. Data stored in the data lake was then transformed using Azure Databricks. Transformations include changing the format of date columns, renaming columns into a uniform state, removing nulls etc.
The transformed data was later pushed into Azure Synapse analytics for further analysis using SQL and then connected with Power BI for reporting. 

PS: This project can be done using lesser number of services. More services were used to further explore Azure cloud.

Snapshot of the dashboard:

![Adventure Works](https://github.com/pranavrj/Azure_E2E/assets/25327428/68c33b58-ad7b-45af-ad95-6580036ded9a)
