# Retail Analysis for a Grocery Store

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)

### Project Overview

This repository contains step by step ETL Pipeline and SQL Scripts to migrate Retail Data from multiple sources into a Staging area and from staging to a Central Data Warehouse Repository on a control framework.

The deliverables for the project are as follows:

- Build an Enterprise Data warehouse that addresses the analytic requirements
- Build Data Mart Cubes for functional areas based on the analytic requirements using SQL Server Analysis Services (Using both Multidimensional and Tabular Models)
- Using Tableau and Power BI to design Data Visualisations for Business Users and Management to enable informed decisions

### Data Sources

- Sales Transaction Data: The dataset used for this analysis is the "Grocery OLTP.bak" file, conataining detailed information about each sale made by the company
- Purchase Transaction Data: The dataset used for this analysis is the "Grocery OLTP.bak" file, conataining detailed information about each sale made by the company
- Overtime Data: The dataset used for this analysis is the "OvertimeData.csv" file, conataining detailed information about the employees' overtime hours
- Misconduct Transaction: The dataset used for this analysis is the "misconduct_trans.csv" file, conataining detailed information about employees' misconducts
- Absent Data: The dataset used for this analysis is the "absent_data.csv" file, conataining detailed information about each employee's absence trends

### Tools
- Microsoft BI stack (SSIS, SSAS, SSRS)
- MS SQL Server Management Studio
- Excel
- Power BI and Tableau (for Data Visualization and creating reports)

### Data Cleaning

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis

This involved exploring the data for all the five (5) Business Processes to answer the following analytic requirements:
- What is selling in the stores each day to evaluate product movement, as well as to see how sales are impacted by promotions
- The mix of products in a customer’s market basket
- Changes to Point of Sales Device on each channel are recorded to know the frequency of channel POS device replacement
- The most ordered products from each Vendor in each store
- The management decided to track changes to vendor information to determine the impact on the delivery services
- Sales Manager is interested to know the effects of product rebranding on Sales
- Human Resources Management needs to know the effects of changes to marital status on salesperson’s overtime hours
- Sales analysis on overall product brand sales and rebrand product sales
- Purchasing Manager needs to know the efficient vendors based on differential days between order date and delivery date
- Sales Manager needs to know what are the most demanding products for each time period of the day
- Employee misconducts analysis is requested by the management as part of the ongoing strategy to improved work ethics and customer satisfaction
- Need to understand Employee Absence trends for performance appraisal and to proactively plan for new employee recruitment to meet the service expectation of Tesca customers
