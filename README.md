## Azure End to End Data Engineering

Project Architecture:


In this project I have migrated 19 tables from MS-SQL Sever (locally hosted) into Azure Data lake using Azure data factory. An ADF pipeline with a parameterized dataset and self hosted IR was setup to copy the data into Azure storage. Data stored in the data lake was then transformed using Azure Databricks. Transformations include changing the format of date columns, renaming columns into a uniform state, removing nulls etc.
The transformed data was later pushed into Azure Synapse analytics for further analysis using SQL and then connected with Power BI for reporting. 
