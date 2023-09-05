# Olympic Data Analytics Azure End-To-End Data Engineering Project

## Getting Started

Before you can start working with this project, you'll need to set up your development environment and Azure resources. Follow these steps:

1. **Azure Account:**
   - If you don't have an Azure account, sign up for one [here](https://azure.com/free).

2. **Azure Storage Account:**
   - Create an Azure Storage Account to store your project's data. You can create one through the Azure portal.
   - Note down the connection string for the storage account.

3. **Azure Data Factory:**
   - Set up an Azure Data Factory instance to handle data ingestion. You can create a Data Factory through the Azure portal.
   - Configure data ingestion pipelines to copy data from your local machine or other sources to the Azure Storage Account.

4. **Azure Databricks:**
   - Create an Azure Databricks workspace to perform data transformation. Set up clusters and notebooks as needed.
   - Develop data transformation scripts using Python or Spark.

5. **Azure Synapse Analytics:**
   - Set up an Azure Synapse Analytics workspace for advanced analytics. Create SQL scripts or notebooks to gain insights from the processed data.

6. **Dashboard Tools:**
   - If you plan to use Power BI, Looker Studio, or Tableau for dashboard creation, ensure that you have the necessary licenses and tools installed on your local machine.

7. **Clone the Repository:**
   - Clone this project repository to your local machine using the following command:

     ```bash
     git clone https://github.com/Youssra1999/Olympic-Data-Analytics-Azure-End-To-End-Data-Engineering-Project
     ```

8. **Set Up Azure Resources:**
   - Configure and set up the necessary Azure resources for your project:

     - **Azure Storage Account:** Create an Azure Storage Account to store your project's data. You can create one through the Azure portal. Note down the connection string for the storage account.

     - **Azure Data Factory:** Set up an Azure Data Factory instance to handle data ingestion. You can create a Data Factory through the Azure portal. Configure data ingestion pipelines to copy data from your sources to the Azure Storage Account.

     - **Azure Databricks:** Create an Azure Databricks workspace to perform data transformation. Set up clusters and notebooks as needed. Develop data transformation scripts using Python or Spark.

     - **Azure Synapse Analytics:** Set up an Azure Synapse Analytics workspace for advanced analytics. Create SQL scripts or notebooks to gain insights from the processed data.

   Follow the specific Azure documentation and guidelines for creating and configuring these services to align them with your project's requirements.


9. **Configuration:**
   - Update the project's configuration files to include the necessary Azure connection strings, storage account details, and other settings.

10. **Download the Dataset:**
    - Download the 2021 Olympics in Tokyo dataset from [this Kaggle link](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo). Place the downloaded dataset files in the `data` directory of your project.

## Project Architecture

To visualize the architecture of this project, please refer to our Miro board:

[![Miro Project Architecture](project_architecture.PNG)](https://miro.com/app/board/uXjVMoiTrbM=/?share_link_id=195135166585)

### Data Sources

The project's architecture includes five primary data sources in the form of CSV files:
1. Athletes Data
2. Coaches Data
3. Entries by Gender Data
4. Medals Data
5. Teams Data

### Data Ingestion

Data ingestion is handled by Azure Data Factory, which efficiently brings in data from the CSV files into our data processing pipeline.

### Raw Data Storage

Our raw data is stored in Azure Data Lake Gen2, providing a scalable and secure repository for large datasets.

### Data Transformation

Azure Databricks is used for data transformation, enabling us to process and refine the raw data into a more structured and usable format.

### Transformed Data Storage

The transformed data is stored back in Azure Data Lake Gen2, making it accessible for further analysis.

### Analytics

Azure Synapse Analytics is employed for advanced analytics and data exploration, allowing us to gain insights from the processed data.

### Dashboard Creation

We create visually compelling dashboards using a combination of tools:
- Power BI: For interactive data visualizations and reporting.
- Looker Studio: For data exploration and analytics.
- Tableau: For creating interactive and insightful dashboards.

## About Miro

[Miro](https://www.miro.com/) is an online collaborative whiteboard platform that enables teams to work visually, brainstorm ideas, plan projects, and more. In the context of our project, we've used Miro to visually represent the architecture, data flows, and components involved in our Olympic Data Analytics solution. It allows for better communication and understanding of our project's design and structure.

## Description

This project is an end-to-end data engineering and analytics solution for the 2021 Tokyo Olympics data. Analyze athlete performance, coach data, and much more!

## Prerequisites

Before you get started with this project, make sure you have the following prerequisites in place:

- **Laptop:** You'll need a laptop or computer to work on this project.

- **Stable Internet Connection:** Ensure you have a stable internet connection for accessing cloud services and resources.

- **Basics of Python and SQL:** Familiarity with Python and SQL will be beneficial for working with data processing and analysis tasks.

- **Azure Account:** You'll need an Azure account to utilize Azure services such as Data Lake Gen2, Azure Data Factory, Azure Databricks, and Azure Synapse Analytics.

## Usage

To utilize this project effectively, follow these steps for interacting with the Azure-based components:

1. **Data Ingestion:**
   - Use Azure Data Factory to manage data ingestion. Configure and execute data ingestion pipelines to bring data into Azure Storage Account.

2. **Data Transformation:**
   - Utilize Azure Databricks for data transformation tasks. Create and run notebooks or jobs to process and refine the raw data stored in Azure Storage Account.

3. **Data Analytics:**
   - Leverage Azure Synapse Analytics to perform advanced analytics and gain insights from the processed data. Create and run SQL scripts or notebooks for data exploration.

4. **Dashboard Creation:**
   - If you plan to create dashboards, use your preferred dashboard tool (e.g., Power BI, Looker Studio, Tableau) to visualize and interact with the analyzed data.

5. **Documentation and Guidelines:**
   - Refer to the project's documentation and guidelines for specific details on using the Azure services, setting up data pipelines, and executing analysis tasks.

6. **Customization:**
   - Customize the project's Azure configurations, data processing logic, and analytics queries to align with your specific use case and requirements.

## Contributors

- [Youssra Abouelmawahib](https://github.com/Youssra1999)


