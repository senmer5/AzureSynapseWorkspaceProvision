# AzureSynapseWorkspaceProvision

## Project Explanation

In this project, I worked with Azure Synapse Analytics to explore and analyze data in a cloud environment. The project involved several tasks that helped me understand the key functionalities of Azure Synapse and how it integrates with Azure Data Lake and SQL pools. Here’s an overview of the steps I completed:

1. **Cloning the repository:**  
   • I started by cloning the DP-203 repository from GitHub, which contains exercises for the Azure Data Engineer certification.  
   • I used PowerShell commands to clone the repo and set up the environment.

2. **Setting up Synapse Analytics:**  
   • After running a PowerShell script to set up the environment, I explored Azure Synapse Studio, which is the interface for managing resources and working with data.  
   • I learned about different components like SQL pools, Apache Spark pools, and Data Lake that are all part of the Synapse workspace.

3. **Ingesting data:**  
   • I created a data pipeline using Azure Synapse Studio to ingest data from an HTTP source (CSV file) into Azure Data Lake Storage.  
   • I used the Copy Data tool to configure the source, destination, and file format settings.

4. **Analyzing data using SQL:**  
   • Once the data was ingested, I used a serverless SQL pool to query the data and perform basic analysis.  
   • I ran SQL queries to retrieve and aggregate data, such as counting products by category.

5. **Analyzing data using Spark:**  
   • I also used an Apache Spark pool to analyze the data using Python (PySpark). This allowed me to perform operations like grouping and counting data.  
   • I visualized the results in Synapse Studio using charts to understand product sales data.

6. **Working with dedicated SQL pools:**  
   • I queried a dedicated SQL pool for a more structured data warehouse approach. This involved working with relational tables and performing JOIN operations to aggregate product sales by month and year.

7. **Deleting resources:**  
   • After completing the exercises, I made sure to delete all the resources created in Azure to avoid unnecessary costs.

## Key Learnings

• **Azure Synapse Analytics:** I gained hands-on experience with the platform, learning how to use its components like SQL pools, Apache Spark pools, and Data Lake to handle large-scale data processing.  
• **Data Pipelines:** I learned how to create and manage data pipelines for ingesting, transforming, and storing data from different sources into Azure Data Lake.  
• **SQL and Spark Pools:** I explored both serverless SQL pools and Apache Spark pools for querying and analyzing data. SQL was great for structured queries, while Spark gave me the flexibility to work with large unstructured datasets using Python.  
• **Resource Management:** I also learned the importance of managing Azure resources and the cost implications of leaving resources running after use. I made sure to pause and delete unnecessary resources.
