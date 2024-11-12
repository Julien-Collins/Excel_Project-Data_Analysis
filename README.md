# My Excel Data Analytics Projects

Greetings! This project details my analysis of jobs within the data industry. Below are two projects, each of which takes on different questions about the data science job industry, as well as methods for analyzing the data. 

## Project 1: Salary Dashboard

This dashboard synthesizes salary data for data-related jobs across various countries and positions. Using a dataset of real-world data science job information from 2023, it provides insights into salary trends based on job titles, locations, and other relevant factors. The goal is to offer a clear and actionable overview of the current job market for data professionals.

[Checkout my work here](https://github.com/Julien-Collins/Excel_Project-Data_Analysis/blob/main/Final_Dashboard_.xlsx)


[Download Final Dashboard](https://github.com/Julien-Collins/Excel_Project-Data_Analysis/raw/main/Final_Dashboard_.xlsx)


![Screenshot 2024-11-11 134440](https://github.com/user-attachments/assets/40754165-23c2-46a4-aefa-6252d31978b9) 


### Excel Skills Used: 

- Charts
- Formulas and Functions
- Data Validation

#### Charts:


![Screenshot - Project 1](https://github.com/user-attachments/assets/315875c4-bffc-4f45-bd30-1d33627ca616)

- Utlized bar chart feature to display the salary data horizontally.
- Sorted jobs by descending values to improve presentation.
- Insights Gained: This quickly identifies salary trends, most notably that senior roles and engineers are higher-paying.


#### Formulas and Functions:

![Screenshot - Project 1 - Code](https://github.com/user-attachments/assets/a55d4e87-af59-4362-abde-6e042120ecbf)


- Filtering by checking job title, country, schedule type, and excluding blank salaries.
- Array Formula created utilizing MEDIAN() function with nested IF() statement to analyze an array.
- This formula populates a table and returns the median salary based on job title, country, and type.

#### Data Validation: 

- Implementing the filtered list as a data validation rule to ensure:
- User input is retricted to validated schedule types
- Incorrect entries are presented
- Overall usabilitiy of the dashboard is enhanced


  ## Conclusion:

This project analyzes job market data to calculate the median salary for specific job titles, countries, and schedules. By filtering out zero salaries and applying multiple conditions (job title, country, and schedule type), it provides a precise, condition-based salary analysis. The goal is to offer actionable insights into salary trends across different job categories, helping professionals and organizations make informed decisions.



## Project 2: Salary Analysis

Here I explore the relationship between the various skills needed per job and the salary associated with those skills. Using more advanced methods on Excel, I was able to draw insighful relationships between these corellary points of data. 

[Download Project 2 Analysis](https://github.com/Julien-Collins/Excel_Project-Data_Analysis/raw/main/Project_2-Analysis.xlsx)

[Checkout my second project here](https://github.com/Julien-Collins/Excel_Project-Data_Analysis/blob/main/Project_2-Analysis.xlsx)


### Questions to Analyze: 

- Do more skills lead to better pay?
- What are the top skills of data professionals?
- What is the pay for the top 10 skills?

### Excel Skills used: 
- Pivot Tables
- Pivot Charts
- DAX (Data Analysis Expressions)
- Power Query
- Power Pivot

#### Power Query (ETL)

- Created two queries from the original data: one with all the data job information and the other listing the skills for each job ID.
- I then transformed each query by modifying the columns in a variety of ways.

![Screenshot - Query Editor - #2](https://github.com/user-attachments/assets/4c39781c-9b69-4532-a637-07a9a4c8f85c)

![Screenshot 2024-#2-AppliedSteps-QueryEditor](https://github.com/user-attachments/assets/09b38981-df57-4625-8755-d6df37e7325a)

#### Pivot Charts & Tables

After extracting, transforming, and cleaning the data, I created a table and chart that includes a regression line to display the relationship between skills requested per job posting and the specifc job posting title. As shown, there is a positive correlation between number of skills requested in job postings and the median salary.

![Screenshot-2](https://github.com/user-attachments/assets/4cd90a04-838d-4f68-bd45-6c8963fb186e)

#### Power Pivot

- I created a data model by integrating the data_jobs_salary and data_job_skills tables into one model.
- I created a relationship between my two tables us the job_id columns

![Screenshot 2024-power pivot](https://github.com/user-attachments/assets/900a5632-6bc8-4b88-a084-50a97d3b595d)
![Screenshot 2024-#2-powerpivotdiagram](https://github.com/user-attachments/assets/8d400a5f-b322-4348-be41-e9fe71a24325)

### Analsyis Question Insights:


![Screenshot 2024-realtopskills](https://github.com/user-attachments/assets/6dbdf7f4-ae79-4bd0-92da-d2c0aab3fa91)

![Screenshot 2024-tablespercentages#2](https://github.com/user-attachments/assets/c581156e-fe14-4e71-b828-5c2cdec12355)



As displayed on the table and chart, it appears that Python and SQL are evidently associated with higher paying roles in the data professional space. These skills are far more likely to appear in requested skills for any job postings, therefore becoming proficient in these is critical to being a sought after candidate.

## Conclusion

As an aspiring data analyst, I used this project to explore the various positions within the industry, as well as the skills, salaries, and locations associated with such positions. Using features like Power Query, Power Pivot, PivotTables, and charts, I was able to draw insightful conlcusions about which skills are worth focusing on, and what data jobs are correlated with higher salaries. Hopefully these insights will inspre other aspiring data professionals. 

