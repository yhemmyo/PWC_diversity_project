# PWC_diversity_project

## Project Overview
### A project to identify and discuss potential root causes for the slow progress in achieving gender balance in all levels in an organization. Relevant factors like rate of hire, performance, promotion and turnover by gender was determined. Project was done on Power BI.

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

**For percentage of turnover,**
```

% Turnover = DIVIDE(
         CALCULATE(COUNT('Pharma Group AG'[In base group for turnover FY20]),'Pharma Group AG'[In base group for turnover FY20]="Y"),
         COUNT('Pharma Group AG'[In base group for turnover FY20]))
```
**Average performance rating for women,**
```
Average performance rating (women) = CALCULATE(AVERAGE('Pharma Group AG'[FY20 Performance Rating]), 'Pharma Group AG'[Gender]="Female")
```
**Percentage of men promoted,**
```
% Men promoted = CALCULATE(DIVIDE([Employees promoted(FY21)], [Employees not promoted(FY21)]+[Employees promoted(FY21)]),'Pharma Group AG'[Gender]="Male")
```
### Findings

1. 59% of the company's employees were male while 41% were female
2. After the first 4 years of employment, the number of female staff began to reduce significantly to that of male
3. Average performance rate of both gender is approximately the same with female having a slightly higher rate of 2.42 and male having  2.41
4. The organization's turnover is 86.80%
5. 3 out of  19 executives are females, 4 out of 33 directors are females, 11 out of 57 senior managers are females. Though females have a slightly higher average performance rate, they are less likely to get higher positions when compared to their male counterpart in the organization
6. Employees within the age of 50-59 have the highest performance rate.
### Recommendations

1. Organisation should look into the reason why women leave after few years, it could be growth restriction, lack of safe space for women, etc.
2. Criteria for executive positions should be stated and equal opportunities should be given to both gender
3. More women (94.3%) worked part-time, part-time work should be considered in order to retain more women.
### Limitations
NONE
