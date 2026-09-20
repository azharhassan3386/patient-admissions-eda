# patient-admissions-eda
# Patient Admissions - Exploratory Data Analysis

## Overview
"Achieved 100% accuracy — this reflects the synthetic nature of the dataset, where Admission_Category was deterministically derived from Primary_Diagnosis, Length_of_Stay, and Comorbidities. On real-world clinical data, such perfect accuracy would indicate data leakage and warrant further investigation."

## Key Analyses
- Monthly admission trends
- Gender distribution
- Admission category vs admission type
- Length of stay distribution and outliers
- Missing value analysis and handling
- Correlation heatmap

## Key Insights
- Most common admission category: Urgent
- Average length of stay: 14.95 days
- Missing data found in Street, Location, Follow_Up, and Notes columns — handled using fillna

## Tools Used
Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook
