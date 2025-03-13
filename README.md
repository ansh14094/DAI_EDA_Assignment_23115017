# DAI_EDA_Assignment_23115017  
**DAI Assignment - Ansh Jain (23115017) CSE**  

### Important 
A separate report file has not been created, as all outcomes and analyses have been documented within the ipynb files as text cells accompanying the code. Additionally, all cell outputs were cleared prior to uploading the notebooks; therefore, visualizations and results are not visible in the current version. Kindly execute the notebooks to generate and view the outputs.

## Employee Attrition Analysis - IBM HR Dataset  

## Overview  

This assignment analyses employee attrition patterns in the IBM HR Analytics Employee Attrition & Performance dataset to identify factors influencing employee turnover and recommend actionable strategies for retention.  

---  

## Key Objectives  

- Perform **data cleaning** to handle missing values, duplicates, outliers, and inconsistencies.  
- Conduct **exploratory data analysis (EDA)** to uncover trends and relationships.  
- Identify **key drivers of attrition** using statistical tests and visualizations.  
- Provide **data-driven recommendations** to reduce employee turnover.  

---  

## Dataset  

- **Source:** IBM HR Analytics Employee Attrition & Performance  
- **Size:** 1,470 employees, 34 features (after cleaning)  
- **Variables:**  
  - **Numerical:** Age, MonthlyIncome, JobSatisfaction, etc.  
  - **Categorical:** Attrition, Department, JobRole, etc.  

---  

## Tasks Performed  

### 1. Data Cleaning  
- Imputed missing values using median for numerical columns.  
- Removed redundant columns (e.g., Over18 with constant value).  
- Capped outliers in MonthlyIncome, DailyRate, and Age using IQR method.  
- Standardized categorical values (e.g., Human Resources → HR, typos fixed).  

### 2. Exploratory Data Analysis (EDA)  
- **Univariate Analysis:** Distributions, summary statistics, frequency tables.  
- **Bivariate Analysis:** Correlation matrices, box plots, and hypothesis testing (e.g., t-tests, chi-square tests).  
- **Multivariate Analysis:** Pair plots, heatmaps, PCA (Principal Component Analysis).  

### 3. Statistical Testing  
- T-tests for income vs. attrition.  
- ANOVA for income variation across departments.  
- Chi-square tests for categorical associations (e.g., attrition vs. department).  
- Decision trees to identify high-risk employee segments.  

---  

## Tools Used  

- **Python Libraries:**  
  - Pandas, NumPy for data manipulation.  
  - Matplotlib, Seaborn for visualization.  
  - SciPy for statistical testing.  
  - Scikit-learn for PCA and modeling.  

- **Statistical Methods:**  
  - Shapiro-Wilk test for normality.  
  - IQR (Interquartile Range) for outlier detection.  
  - PCA for dimensionality reduction and clustering insight.  

- **Visualization Techniques:**  
  - Heatmaps, violin plots, faceted bar charts, pair plots.  

---  

## Outcomes & Recommendations  

- Identified high-risk roles (e.g., Sales Representatives, Lab Technicians) with highest attrition.  
- Found income and job satisfaction as major attrition drivers.  
- Highlighted department-specific trends requiring targeted interventions.  
- Proposed actionable strategies such as career development, revised promotion cycles, and focused retention programs.  

---  
