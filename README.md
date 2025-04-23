# Analysis-of-HR-Attrition-Patterns
Understanding-Employee-Turnover
Tomato Smoothie🍅

A Statistical and Predictive Analysis of HR Attrition Patterns
HR Insight Logo

📊 Overview
This repository presents a detailed statistical and machine learning-driven analysis of employee turnover. The goal is to understand the key drivers behind HR attrition and build predictive models to identify at-risk employees before they leave the organization.

👥 Dataset Description
The analysis utilizes a cleaned HR dataset containing demographic and organizational attributes of employees. Key data files include:

Augmented_HR_Employee_Attrition_4000.csv

🔧 Dependencies
This project is implemented in R and requires the following packages:


library(ggplot2)      # Visualization  
library(dplyr)        # Data manipulation  
library(readr)        # Reading datasets  
library(tidyr)        # Reshaping data  
library(lubridate)    # Handling dates  
library(caret)        # ML models  
library(forcats)      # Factor level management  
library(e1071)        # SVMs and additional ML tools  

📋 Features
Descriptive Statistics: Summary metrics and visual breakdown of attrition

Correlation Heatmaps: Identification of strongly linked attrition factors

Predictive Modeling: Logistic Regression, Decision Trees, and SVMs for attrition prediction

Cluster Analysis: Grouping high-risk employee profiles using unsupervised learning

Temporal Trends: Analysis of monthly, quarterly, and yearly attrition patterns

Workforce Insights: Role-based and department-wise risk evaluation

Recommendations: Data-driven suggestions for improving retention

🚀 Key Findings
Attrition is highest among mid-level employees with 2–5 years of experience

Lack of promotion and low satisfaction are key churn indicators

Attrition peaks during Q1 and Q3, hinting at post-review and pre-fiscal year exits

Machine learning models achieved up to 84.7% accuracy in predicting attrition

R&D and Sales departments consistently show above-average turnover rates

💡 Research Questions
This project answers the following SMART questions:

Specific: What are the main causes of employee turnover?

Measurable: How do satisfaction levels and promotions correlate with attrition?

Achievable: Can a model accurately predict employee exits in advance?

Relevant: Which departments are most vulnerable to losing talent?

Time-bound: What are the seasonal trends in attrition over the last 3 years?

📊 Usage
To run the analysis:

Clone this repository

Install the necessary R packages

Place all CSV files inside the /data directory

Open and run employee_turnover_analysis.Rmd

View the resulting HTML output for the full report

📈 Sample Visualizations
Attrition by Department
Bar plot showing turnover rates across departments

Predictive Accuracy of Models
Chart comparing accuracy of different models used in the analysis

🔗 References
IBM HR Analytics Attrition Dataset

Harvard Business Review: Predicting Employee Turnover

SHRM Workforce Retention Reports

📄 License
This project is licensed under the MIT License. See the LICENSE file for full details.

👤 Author
Tomato Smoothie🍅
