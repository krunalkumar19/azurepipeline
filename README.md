# MS Azure pipeline
## Azure Data Pipeline with Databricks

## This repository contains a Databricks notebook demonstrating data transformation using PySpark in an Azure Data Pipeline. The project showcases ETL (Extract, Transform, Load) workflows using Azure Data Lake Storage, Databricks, and Spark.

## This is a code repository. So, in case you are looking to build the pipeline, please connect with me at kapadiakrunal7@gmail.com 

## 🚀 Features
- Reads data from **Azure Data Lake Storage (ADLS)**
- Performs data **cleaning and transformations** using **PySpark**
- Stores the transformed data back into **ADLS (Silver/Gold layers)**
- Optimized for **big data processing** in **Databricks**

## 🛠️ Technologies Used
- **Azure Data Lake Storage (ADLS)**
- **Azure Databricks**
- **Apache Spark**
- **PySpark**
- **Delta Lake (if applicable)**
- **GitHub for version control**

## Pipeline Structure
![image](https://github.com/user-attachments/assets/4c4be6c7-de09-447b-adf0-9d8567de42c1)
- **LookupForEachInput**: This pipeline shows the file lookup action for raw CSV files from APIS
- **ForEach**: Iteration function to copy data from HTTPS instances and get it in storage.
- **Copy Data**: Copy data from the MYSQL server and get it in the storage.

## 📂 Repository Structure
- **Medallion** Architecture
- 3 folder structure with name **"Bronze", "Silver", "Gold"** showing the data preparation in that folder.
- ![image](https://github.com/user-attachments/assets/e3d37c5e-0c4c-451b-9929-e59c6b65dc09)

- ## Bronze Folder:
- ![image](https://github.com/user-attachments/assets/4aca0bc3-6df3-47c4-bb78-927db8ff9d32)
- This folder shows the source data connected by the pipeline shown above. These are raw CSV files to be modified for analysis use.
  
- ## Silver Folder:
- ![image](https://github.com/user-attachments/assets/2fe96afc-3f38-4fb9-bc99-348083aafa63)

- ## Gold Folder:
- ![image](https://github.com/user-attachments/assets/677715c6-a668-417e-86f6-88d4ddd34e41)
  






