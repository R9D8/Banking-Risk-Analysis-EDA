
# Risk Analytics in Banking: Loan Approval EDA

## Introduction
This project is focused on performing Exploratory Data Analysis (EDA) to aid a consumer finance company in making informed decisions regarding loan approvals. The primary objective is to minimize the risk of financial losses that may occur from lending to applicants likely to default on their loans.

## Problem Statement
Loan providing companies often struggle with loan approvals due to insufficient or non-existent credit histories of applicants, leading to potential defaults. This project uses EDA to analyze patterns in the data to ensure that applicants who are capable of repaying the loan are not unjustly rejected.

## Business Understanding
The decision to approve a loan involves assessing the risk associated with the applicant's potential to default. The dataset includes various scenarios such as clients with payment difficulties and those who have maintained timely payments. This analysis aims to identify strong indicators of default, which can help the company in portfolio and risk assessment.

## Dataset Overview
The dataset comprises three files:
1. `application_data.csv` - Contains data at the time of the loan application.
2. `previous_application.csv` - Includes information on the client’s previous loan applications.
3. `columns_description.csv` - A data dictionary that describes the meaning of the variables used in the dataset.

## Objectives
- To perform a comprehensive EDA to uncover the underlying patterns that signify the risk associated with loan applications.
- To identify critical factors that influence loan defaults and utilize this information to enhance the company’s loan approval processes.

## Analysis Approach
- Handling missing data by appropriate imputation methods based on the analysis context.
- Identifying and interpreting outliers in the dataset.
- Analyzing data imbalance with respect to the target variable (clients with payment difficulties).
- Exploring relationships between variables through univariate, bivariate, and segmented analysis.
- Discovering top correlations among variables to pinpoint key drivers of loan defaults.

## Results
Detailed insights from the analysis will be presented, highlighting the variables most indicative of payment difficulties. This information will be crucial for risk management and decision-making regarding loan approvals.

## Technologies Used
- Python for data manipulation and analysis.
- Libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data handling and visualization.

## Files
1. IPython Notebooks containing the detailed analysis and visualizations.
2. Presentation PDF summarizing the analysis and key findings.
