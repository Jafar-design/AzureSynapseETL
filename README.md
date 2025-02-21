# 🚀 Azure Synapse Analytics Data Ingestion Project

## 📌 Overview
This project demonstrates how to ingest raw data in CSV and Parquet formats into Azure Synapse Analytics. The data is stored in Azure Data Lake Storage Gen2 by default and processed using Azure Synapse capabilities. The project is designed to provide hands-on experience with data ingestion, transformation, and querying in Synapse Analytics.

## ✅ Prerequisites
Before you begin, ensure you have the following:
- 🔹 An **Azure Account** with access to Azure Synapse Analytics and Azure Data Lake Storage Gen2.
- 🔹 Basic knowledge of **Python/PySpark** for working with data in Synapse.
- 🔹 The raw data in **CSV and Parquet format** ready for ingestion.

## 🎯 Project Scope
- 📥 **Data Ingestion:** Load raw data into Azure Synapse Analytics from Azure Data Lake Storage Gen2.
- 🔄 **Data Processing:** Utilize Azure Synapse pipelines and notebooks to transform and analyze the ingested data.
- 📊 **Querying & Reporting:** Use Synapse SQL to query data for insights and analytics.

## 🛠️ Setup Instructions
1. **Provision Azure Synapse Analytics:**
   - 🏗️ Create a Synapse workspace in Azure.
   - 🗄️ Set up an Azure Data Lake Storage Gen2 account for raw data storage.
   
2. **Upload Data to Data Lake Storage Gen2:**
   - 📂 Store CSV and Parquet files in a designated container within the storage account.
   
3. **Configure Linked Services in Synapse:**
   - 🔗 Connect Synapse Analytics to the Data Lake Storage account.
   - 🔐 Ensure necessary permissions and roles are assigned.
   
4. **Ingest Data into Synapse:**
   - 🚛 Use Synapse Pipelines or notebooks to load data into dedicated SQL pools.
   - 🐍 Utilize PySpark in Synapse notebooks for additional transformations.

5. **Run Queries in Synapse SQL:**
   - 🧐 Execute SQL queries on the ingested data to validate and analyze the results.
   
## 📚 Resources
- 📖 Project Presentation: [View Here](https://docs.google.com/presentation/d/1qoqlc4f7_fBXZU2NhXjXs4s2ORLo3peQqkk2JfPi3q0/edit#slide=id.g35f391192_00)
- 📝 Sample Code from @dvannoy: [GitHub Repository](https://github.com/datakickstart/synapse_examples/blob/main/data_lake_load.ipynb)

## 📜 License
This project includes code credited to [@dvannoy](https://github.com/datakickstart) and follows the licensing terms provided in the linked GitHub repository.

## 📩 Contact
For any inquiries or contributions, feel free to reach out or open an issue in the project repository.

