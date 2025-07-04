# DSA-Documentation Using Power-BI
## Project Topic: Palmoria Group
### Introduction / Overview
The goal of this project is to analyze employee compensation data from Palmoria, a manufacturing company, to assess compliance with a new regulation mandating a minimum salary of $90,000 for all employees. The dataset contains demographic and employment information including region, gender, department, and salary.
This analysis will:
•	Identify compliance gaps.
•	Provide salary distribution trends.
•	Deliver actionable insights using Power BI visuals and data exploration.

### Data Cleaning and Preparation
Steps taken to prepare the data:
- Removed Null Entries: 
   - Rows with missing Department or Salary fields were filtered. 
- Created New Columns: 
   - Salary Band: Grouped employees in salary ranges of $10,000 (e.g., $90k–$100k), using conditional column
   - Bonus_Amount: salary * bonus = total bonus
- Gender Classification: 
   - Filled missing gender using common name inference "Generic".
- Created a Merger between palmoria group Hr and Bonus rules using rating and department as primary key
- Unpivot bonus rules

### Project Objectives
- Assess Compliance with the new $90,000 salary regulation.
- Understand Pay Distribution across bands and regions.
- Identify Disparities in salary by gender, department, and location.
- Provide Visual Reports for stakeholders using Power BI.
- Understand the Total salary paid

### Exploratory Data Analysis (EDA)
Key variables explored:
- Salary Distribution: 
   - Histogram and boxplot show skewness toward lower salary brackets.
- Region-wise Salary: 
   - Average salary and compliance % vary significantly across regions.
- Department Breakdown: 
   - Some departments (e.g., Manufacturing) have lower average pay than Admin or Tech.
- Gender Pay Analysis: 
   - Gender distribution is unequal in some departments; potential pay gap noted.
- Salary Bands: 
   - Created bands (e.g., $10k–$20k, $20k–$30k, ..., $140k+) to visualize frequency.
- Sum of Salary:
   - total salary in addition to the bonus

Key Insights
- Non-Compliance Detected:
   - Over 40% of employees earn below $90,000.
   - High concentration in $70k–$80k band.
- Regional Disparities:
   - Some regions like West and South-East show significantly lower average salaries and higher non-compliance.
- Departmental Trends:
   - Tech and Admin departments have the highest compliance.
   - Manufacturing has the largest headcount but lowest compliance rate.
- Gender Gap Possibility:
   - Male employees dominate higher-paying roles.
   - Female employees are underrepresented in high-paying departments.
- Salary Distribution:
   - The distribution shows a bell shape peaking at $70k–$90k.
   - Drastic drop in counts beyond the $100k+ range.






