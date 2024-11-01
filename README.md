# Hr Data Analysis with Power BI 

### Project Overview

This project aims to gain insight into employee demographics, performance and attrition rate. Utilizing Power BI and guidance from my facilitator at The Incubator Hub, I created an interactive and informative report, extracting valuable insights.  This project showcases my skills in data modelling, visualization, dashboard design and DAX formula writing, demonstrating my ability to work with HR datasets and extract actionable recommendations.

### Data Source 

The original dataset 'HR Data' used for this project was provided by The Incubator Hub as part of Their Data Analysis Training resources. 

### Tools Used 

- Power Bi
  1. For Data Cleaning and Preparation 
  2. For Data Analysis
  3. For DAX Calculation
  4. For Dashboard report and Visualization
- GitHub - For Portfolio Building 

### Data Cleaning and Preparation 

To ensure Data accuracy, we performed the following preprocessing steps: 
1. Checking data quality and consistency
2. Analyzing data Profile and distribution
3. Promoting first column as header

 ### Exploratory Data Analysis

 We explored the HR Data to answer key questions such as: 
1. What is the total number of employees?
2. What is the number of current employees?
3. What is the total number of attrition count?
4. What is the attrition rate?
5. What is the attrition count by department?
6. What is the attrition count by educational field?
7. What is the attrition count by gender?
8. What is the count of current employees by gender?
9. What is the marital status of current employees?
10. What are the job roles and satisfaction/dissatisfaction levels?
11. What is the attrition rate by age bands?

### Data Analysis 

1. Measures
- Attrition Rate
```DAX
Attrition Rate = SUM('HR data'[Attrition Count]) / SUM('HR data'[Employee Count])
```
- Average Age of Employee
```DAX
AVG Employee AGE = AVERAGE('HR data'[Age])
```
2. Conditional Columns
- Attrition Count
-  Age Sort
-  job Satisfaction Rating 
