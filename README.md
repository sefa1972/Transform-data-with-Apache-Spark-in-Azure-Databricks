# Transform Data with Apache Spark in Azure Databricks

This project is a hands-on lab designed to teach data transformation steps in an **Azure Databricks** environment using **Apache Spark**. Throughout the lab, you will perform tasks such as loading, cleaning, filtering, aggregating, and querying data using SQL.

## Objectives

- Understand the fundamentals of big data processing with Apache Spark  
- Perform analysis and transformations on data using notebooks in Azure Databricks  
- Query data using Spark SQL  
- Gain practical experience in preparing data for real-time analysis

## Requirements

- An active **Azure subscription**  
- A **Databricks workspace** created in Azure  
- Access to Azure Cloud Shell or PowerShell  
- A system with Git installed

## Technologies Used

- Apache Spark (PySpark)  
- Azure Databricks  
- Python  
- Spark SQL  
- Azure Cloud Shell

## Steps

### 1. Environment Setup

Use Azure Cloud Shell to run the following commands to download the necessary files and configurations:

```powershell
git clone https://github.com/MicrosoftLearning/mslearn-databricks
cd mslearn-databricks
./setup.ps1
```

### 2. Create Databricks Cluster

- **Cluster mode**: Single Node  
- **Runtime**: 13.3 LTS (Photon enabled)  
- **Node type**: Standard_D4ds_v5  
- **Auto termination**: 20 minutes

### 3. Create and Attach Notebook

- Create a new notebook named `Transform data with Spark`  
- Select PySpark as the language  
- Attach it to the newly created cluster

### 4. Load the Data

Upload CSV files to Databricks and load them into dataframes using PySpark.

### 5. Data Transformation Operations

- **Cleaning**: Remove duplicates and convert data types  
- **Filtering**: Filter customers based on specific products  
- **Aggregation**: Analyze product sales and yearly order counts  
- **SQL**: Use temporary views and Spark SQL for querying

### 6. Clean Up

After completing the lab, terminate the Databricks cluster to free up resources.

### 👤 Author >>  Sefa Öztürk

IT Trainee | Azure Data Engineer in progress

📇 LinkedIn: https://www.linkedin.com/in/sefa-ozturk1972

