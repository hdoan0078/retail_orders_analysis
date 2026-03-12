# retail_orders_analysis
# Retail Sales Performance Using Python and SQL
# Project Overview

Project Overview

Retail companies generate large volumes of transaction data every day, including information about products sold, order dates, customer locations, pricing, and discounts. However, raw transactional data alone does not provide clear answers to key business questions such as:
- Which products generate the most revenue?
- Which regions drive the strongest sales performance?
- How are sales trends evolving over time?
- Which product categories are growing and which are declining?
The goal of this project was to build an end-to-end data analysis pipeline that transforms raw retail transaction data into meaningful business insights.

To accomplish this, I developed a workflow that combines Python for data preparation and SQL for business analysis. The project begins with retrieving a retail dataset using the Kaggle API, followed by data cleaning and feature engineering in Python using Pandas. After preparing the dataset, the processed data is loaded into SQL Server, where SQL queries are used to answer business questions related to revenue performance, regional demand, and product growth trends.

This project demonstrates a typical data analyst workflow, moving from raw data to actionable business insights.


# Data Acquisition

The first step in the project was obtaining the dataset. Instead of manually downloading files, I used the Kaggle API to retrieve the dataset programmatically. This approach improves reproducibility and allows datasets to be integrated easily into automated workflows.

The dataset used in this project is the Retail Orders dataset, which contains approximately 10,000 retail transactions across multiple product categories and regions in the United States.

Using the Kaggle API, the dataset was downloaded directly into the Jupyter Notebook environment.

```dax
!pip install kaggle
!kaggle datasets download ankitbansal06/retail-orders -f orders.csv
```
