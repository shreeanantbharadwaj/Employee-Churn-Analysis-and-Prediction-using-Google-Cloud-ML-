
 # Google Cloud-Based Employee Churn Prediction and Analysis

This repository holds an end-to-end project focused on predicting and analyzing employee churn using Google Cloud services. The goal is to help organizations proactively identify employees at risk of leaving and implement retention strategies more effectively.

## Link to Interactive Dashboard:
https://lookerstudio.google.com/reporting/7e391a5d-6cfd-41c9-8e7f-9346b96d77c7

## Project Agenda

The project consists of the following key phases:

1. **Building the Database**: Utilizing BigQuery, we structure a database that captures the necessary employee data for analysis.
2. **Database Connectivity**: Establish a connection to BigQuery using Python within a Google Colab environment, allowing for data manipulation and analysis.
3. **Churn Model Development**: Implement a churn prediction model using PyCaret, an open-source, low-code machine learning library in Python.
4. **Data Exportation**: Streamline the process for exporting processed and model output data back to BigQuery for persistence and further use.
5. **Dashboard Creation**: Develop an interactive dashboard using Looker Studio to visualize the insights and findings from our churn model.

## Problem Statement

Employee retention is a critical challenge for many organizations. This project aims to address the difficulty of retaining employees by leveraging data analytics and machine learning to identify employees who are at a high risk of leaving the company.

## Approach

- A pilot program is selected, focusing on new employees.
- An AutoML model is constructed, trained on historical data, to predict the likelihood of new employees leaving the company.


## Deliverables

A comprehensive report detailing the findings from the data analysis and model predictions.
An interactive dashboard created in Looker Studio, providing a visual representation of the data and insights for easy interpretation by stakeholders.

## How to Use This Repository

Clone the repository to your local machine.
Follow the steps outlined in the agenda to replicate the project within your own Google Cloud environment.
Utilize the Jupyter notebook provided (Employee_Churn_analysis.ipynb) as a guided walkthrough for building and deploying the churn model.

## Contributions

Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements.
