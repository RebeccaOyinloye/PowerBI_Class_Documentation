# Hr Data Analysis with Power BI 

## Table of Content

[Project Overview](#Project-overview)

[Data Source](#data-source)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Findings and Results](#findings-and-results)

[Recommendations](#recommendations)

[Limitation](#limitation)

[Conclusion](#conclusion)

### Project Overview
---
This project aims to gain insight into employee demographics, performance and attrition rate. Utilizing Power BI and guidance from my facilitator at The Incubator Hub, I created an interactive and informative report, extracting valuable insights.  This project showcases my skills in data modelling, visualization, dashboard design and DAX formula writing, demonstrating my ability to work with HR datasets and extract actionable recommendations.

### Data Source 
---
The original dataset 'HR Data' used for this project was provided by The Incubator Hub as part of Their Data Analysis Training resources. 

### Tools Used 
---
- Power Bi
  1. For Data Cleaning and Preparation 
  2. For Data Analysis
  3. For DAX Calculation
  4. For Dashboard report and Visualization
- GitHub - For Portfolio Building 

### Data Cleaning and Preparation 
---
To ensure Data accuracy, we performed the following preprocessing steps: 
1. Checking data quality and consistency
2. Analyzing data Profile and distribution
3. Promoting first column as header

 ### Exploratory Data Analysis
---
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
---
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

### Findings and Results
---
The analysis uncovered several significant trends in employee attrition:

- The R&D department has the highest attrition rate.
- Life Sciences and Medical fields exhibit high attrition rates.
- The Sales department records a high attrition count.
- Male employees display a higher attrition rate.
- Technical Degree holders also experience high attrition rates.
- Divorced employees have a higher attrition rate. In contrast, married employees report a higher job satisfaction rate.

### Recommendations 
---
Based on the analysis, I recommend the following actions: 

- Implement targeted retention initiative in the sales department 
- Enhance the work environment and benefit in R&D department 
- Build on existing strategies to maintain high job satisfaction among married employees 
- Offer competitive salary and benefits to technical degree holder
- Develop program to promote diversity

### Limitation 
---
This analysis has minimal limitations due to the high-quality dataset. The data cleaning and exploration process using Power BI ensured:

- 100% column quality validity
- Accurate and complete data

### Conclusion 
---
This analysis identified significant trends in employee attrition, highlighting areas for improvement.
By implementing these strategies, the organization can reduce attrition, improve job satisfaction, and promote a more inclusive work environment.
