# Analysis-of-HR-Attrition-Patterns
Understanding-Employee-Turnover
Tomato Smoothie🍅

A Statistical and Predictive Analysis of HR Attrition Patterns
HR Insight Logo

📊 Overview
This repository presents a detailed statistical and machine learning-driven analysis of employee turnover. The goal is to understand the key drivers behind HR attrition and build predictive models to identify at-risk employees before they leave the organization.

👥 Dataset Description
The analysis utilizes a cleaned HR dataset containing demographic and organizational attributes of employees. Key data files include:

employee_attrition.csv: Main dataset with employee-level information

turnover_trends.csv: Historical monthly turnover data

satisfaction_scores.csv: Employee satisfaction across various parameters

promotion_salary.csv: Records of promotions and compensation changes

job_roles_breakdown.csv: Attrition trends across different job roles and departments

exit_reason_tags.csv: Annotated reasons for employee exits

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