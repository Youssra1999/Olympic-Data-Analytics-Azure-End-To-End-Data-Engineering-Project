# Olympic Data Analytics Azure End-To-End Data Engineering Project

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

[Add a brief description of your project here.]

## Getting Started

[Include instructions on how to set up and run your project.]

## Usage

[Provide information on how to use your project or any relevant commands.]

## Contributors

[List the contributors to your project.]

## License

[Specify the license for your project, if applicable.]
