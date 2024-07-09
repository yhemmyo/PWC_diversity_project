# PWC_diversity_project

## Project Overview
### A project to identify and discuss potential root causes for the slow progress in achieving gender balance at the executive management level in an organization. Relevant factors like rate of hire, performance, promotion and turnover by gender was determined. Project was done on Power BI.

### Data Source
Data was gotten from the [PWC Power BI Internship on Forage](https://www.theforage.com/simulations/pwc-ch/power-bi-cqxg)


### Tools

- Excel for data cleaning
- Power BI for measures and visualizations

### Data Preparation
- Duplicates were removed from data on Excel
- Empty cells were removed
- Irrelevant cells like "region group nationality 1" was removed

### Exploratory Data Analysis
EDA considered the data explored and measures to define proper KPIs and answer some of the major problem, such as:

1. Number of men in the organization

2. Number of women in the organization
3. Number of leavers
4. Percentage of employees promoted
5. Percentage of women promoted
6. Percentage of hires men
7. Percentage of hires women
8. Percentage of turnover
9. Average performance rating of men and women
10. Numbers of employees in each department
11. Gender of each employee in a management role



### Data Analysis
Interesting code/features worked with using Power BI measures
'''

% Turnover = DIVIDE(
         CALCULATE(COUNT('Pharma Group AG'[In base group for turnover FY20]),'Pharma Group AG'[In base group for turnover FY20]="Y"),
         COUNT('Pharma Group AG'[In base group for turnover FY20]))
'''

### Findings

### Recommendations

### Limitations
2 How many days has each customer visited the restaurant?
