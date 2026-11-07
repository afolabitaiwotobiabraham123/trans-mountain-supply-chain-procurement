# Python Data Analysis

This folder contains the Jupyter Notebooks used for data acquisition, exploratory data analysis, data quality assessment, and data cleaning and preparation for the Trans Mountain Supply Chain, Procurement & Forecasting Analytics project.

Python, Jupyter Notebook, and Pandas will be used to retrieve, explore, assess, transform, and prepare procurement and supply chain datasets for further analysis.

## Notebooks

### 01_data_acquisition.ipynb
Identifies and acquires relevant procurement and supply chain datasets from selected data sources. Original datasets will be preserved in the raw data folder.

### 02_exploratory_data_analysis.ipynb
Explores the collected datasets to understand their structure, variables, distributions, purchasing patterns, supplier information, material demand, and delivery performance.

### 03_data_quality_assessment.ipynb
Assesses the datasets for missing values, duplicate records, invalid values, inconsistent categories, date-related issues, and data-type problems.

### 04_data_cleaning_and_preparation.ipynb
Cleans, transforms, and prepares the datasets using Pandas, documenting preparation decisions and producing structured datasets for MySQL analysis and forecasting.

## Tools
- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- Requests (where API data acquisition is required)

## Workflow
Data Acquisition → Exploratory Data Analysis → Data Quality Assessment → Data Cleaning and Preparation

**Note:** Forecasting model development and evaluation will be documented separately in the forecasting folder.
