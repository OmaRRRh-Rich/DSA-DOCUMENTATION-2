# DSA-Documentation Using Power-BI
## Project Topic: Palmoria Group
### Introduction / Overview
The goal of this project is to analyze employee compensation data from Palmoria, a manufacturing company, to assess compliance with a new regulation mandating a minimum salary of $90,000 for all employees. The dataset contains demographic and employment information including region, gender, department, and salary.
This analysis will:
•	Identify compliance gaps.
•	Provide salary distribution trends.
•	Deliver actionable insights using Power BI visuals and data exploration.
### Data Sources
The primary source of data used is the Palmoria group.csv and palmoria bonus.excel, it was provided by the incubator hub as our final project
### Tools Used
 - PowerBI [Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads?ocid=ORSEARCH_Bing&msockid=0b06a1a0c36e6a270efdb7a4c21e6b87)
   - Data Cleaning
   - Creating Report

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

### Key Insights
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

### Data Analysis
I applied these steps in other to answer the questions, using steps in this image
<img width="227" height="262" alt="image" src="https://github.com/user-attachments/assets/2ffb2aa2-b534-47e2-883c-1deabb8ae71b" />

### Visualization
<img width="735" height="416" alt="image" src="https://github.com/user-attachments/assets/518f3847-59a1-4f34-9a20-88a2e59b1c7d" />
<img width="732" height="396" alt="image" src="https://github.com/user-attachments/assets/fb7fb5a0-be63-462a-a296-3d1fcd1236dd" />
<img width="734" height="424" alt="image" src="https://github.com/user-attachments/assets/10a590cd-eaee-4449-82b1-2fa6e24a418a" />

### Recomendations
- Conduct a salary audit across roles to identify unjustified disparities.
- Investigate possible regional management or structural biases in promotions or hiring standards.
- Introduce regional HR oversight or training to align practices across locations.
- Benchmark Manufacturing compensation against industry standards.
- checks Implement bias in promotion/hiring systems and review hiring pipelines.
- Promote internal female mobility into high-paying departments (e.g., Tech).
- Consider spot bonuses or equity incentives to retain mid-level talent stuck in the bell curve.
  
### Limitations
During my work, after i had merged i was unable to close and apply due to duplication on my bonus rules table, which occured after i got the other columns unpivoted.
There was no unnecessary columns rather some rows were taken out

### References
Power BI

incubator hub [youtube]









