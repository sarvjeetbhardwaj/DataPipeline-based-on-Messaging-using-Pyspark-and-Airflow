# DataPipeline-based-on-Messaging-using-Pyspark-and-Airflow

# Project Overview
This project involves straeming real-time data with Nifi, parse json to csv store in HDFS, process with Pyskark and Kafka, create Hive Table and deploy to datalake . Visualization with Tableau and AWS QuickSight for insights on data

# Aim
Aim of the project is to get insights on the ingested covid data 

# TechStack Used
    - Nifi
    - Kakka
    - PySpark
    - Hadoop
    - Airflow
    - Tableau

# Approach
    1. Extract data from external source using API
    2. Process using Nifi
    3. Store the one set of raw result in HDFS
    4. Send the another set of raw data to Kafka for pre-processing using PySpark
    5. Processed data will be store in HDFS in another location
    6. Create an external hive table
    7. Cleaned transformed is stored in datalake
    8. Perform Visualization using Tableau

# Application Flow
![alt text](image.png)


    