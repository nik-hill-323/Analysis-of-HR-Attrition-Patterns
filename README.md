# 🍅 Analysis of HR Attrition Patterns  
**Understanding Employee Turnover**  
*by Tomato Smoothie*

---

## 📊 Overview
This repository presents a comprehensive **statistical and machine learning-based analysis** of employee attrition. The goal is to uncover the key drivers behind workforce turnover and build predictive models to identify employees at risk of leaving.

---

## 👥 Dataset Description
We use a curated and cleaned HR dataset that includes both **demographic and organizational attributes** of employees.

**Key file:**
- `Augmented_HR_Employee_Attrition_4000.csv`

---

## 🔧 Dependencies
This project is built using **R**. Make sure the following packages are installed:

```r
library(ggplot2)         # Visualization  
library(dplyr)           # Data manipulation  
library(readr)           # Reading datasets  
library(tidyr)           # Data reshaping  
library(lubridate)       # Date handling  
library(caret)           # ML workflows  
library(forcats)         # Factor management  
library(e1071)           # SVMs and ML tools  
library(tidyverse)       # Unified data manipulation and visualization  
library(corrplot)        # Correlation heatmaps  
library(randomForest)    # Random Forests  
library(rpart)           # Decision trees  
library(rpart.plot)      # Decision tree plots  
library(cluster)         # K-means clustering  
library(factoextra)      # Cluster visualizations  
library(gridExtra)       # Plot layout  
library(grid)            # Grid graphics  
library(scales)          # Scale formatting  
library(ResourceSelection) # Hosmer-Lemeshow test  
library(pROC)            # ROC curves  
library(knitr)           # Report tables  
library(kableExtra)      # Enhanced table output  
library(viridis)         # Color palettes
```

---

## 📋 Features
- **📊 Descriptive Statistics**: Summary metrics and visual breakdown of attrition.
- **🧬 Correlation Analysis**: Identify variables most strongly associated with turnover.
- **🔍 Predictive Modeling**: Logistic Regression, Decision Trees, and SVMs.
- **👥 Clustering**: Unsupervised grouping of high-risk employee profiles.
- **🗕️ Temporal Trends**: Monthly, quarterly, and yearly turnover patterns.
- **🏢 Workforce Insights**: Risk segmented by department and role.
- **📈 Data-Driven Recommendations**: Practical suggestions to reduce attrition.

---

## 🚀 Key Findings
- Attrition is highest among **mid-level employees** (2–5 years tenure).
- **Lack of promotion** and **low job satisfaction** are key churn indicators.
- Turnover spikes in **Q1 and Q3**, likely due to performance cycles.
- Models achieved up to **84.7% prediction accuracy**.
- **R&D and Sales** departments consistently show elevated attrition.

---

## 💡 Research Questions
This project is guided by SMART research questions:

- **Specific**: What are the key drivers of employee turnover?
- **Measurable**: How do satisfaction and promotions correlate with attrition?
- **Achievable**: Can we accurately predict employee exits?
- **Relevant**: Which departments are most vulnerable?
- **Time-bound**: What are the seasonal attrition patterns over 3 years?

---

## 🛠️ Usage

1. Clone this repository  
2. Install all required R packages  
3. Place all CSV files in the `/data` directory  
4. Open and run `employee_turnover_analysis.Rmd`  
5. View the generated HTML report

---

## 📈 Sample Visualizations

### Attrition by Department
Bar chart highlighting turnover rates across departments.

### Model Accuracy Comparison
Plot showing accuracy of different ML models used.

---

## 🔗 References
- IBM HR Analytics Attrition Dataset  
- *Harvard Business Review*: Predicting Employee Turnover  
- *SHRM*: Workforce Retention Reports

---

## 📄 License
This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

---

## 👤 Author
**Tomato Smoothie** 🍅  
_Data Enthusiast & Human Behavior Explorer_
