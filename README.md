# Data-Analysis-in-Excel
Job Postings Analysis in Excel (The Job Postings dataset is a smaller part of the data used in my [Data-Job-Postings-Analysis-2023](https://github.com/EtayDabach/Data-Job-Postings-Analysis-2023) database)

This analysis is divided into two:

* Salary Dashboard, which is a simple UI that displays the median salary, most popular job posting site, and job count based on job title, country, and job schedule.

* Advanced Analysis, a more complex analysis of the data where I answer the questions: What are the top skills for each role? Do more skills equal more money? What is the salary for the top 10 skills? This is based on the job title and country given.


## Salary Dashboard
![Salary dashboard gif](./Salary_Dashboard/Salary_Dashboard_GIF.gif)

The following Excel skills were utilized for analysis:

- **Charts**
- **Formulas and Functions**
- **Data Validation**


## Advanced Analysis
![Advanced analysis gif](./Advanced_Analysis/Advanced_Analysis_GIF.gif)

The following Excel skills were utilized for analysis:

- **Pivot Tables**
- **Pivot Charts**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL)**
- **Power Pivot**

### Skill: Power Query (ETL)

#### Extract

- I first used Power Query to extract the original data (`data_salary_all.xlsx`) and create two queries:
    - First one with all the data jobs information.
    - The second listing the skills for each job ID.

#### Transform

- Then, I transformed each query by changing column types, removing unnecessary columns, cleaning text to eliminate specific words, and trimming excess whitespace.
    - data_jobs_all
    - data_job_skills

#### Load

- Finally, I loaded both transformed queries into the workbook, setting the foundation for my subsequent analysis.
    - data_jobs_all (2)  * I referred from the originals for trial and error.
    - data_job_skills (2)

<!--
#### Analysis

- There is a positive correlation between the number of skills requested in job postings and the median salary, particularly in roles like Senior Data Engineer and Data Scientist.
- Roles that require fewer skills, like Business Analyst, tend to offer lower salaries, suggesting that more specialized skill sets command higher market value.
- This trend emphasizes the value of acquiring multiple relevant skills, particularly for individuals aiming for higher-paying roles.
-->


