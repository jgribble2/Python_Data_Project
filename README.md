## OVERVIEW 

Welcome to my analysis of the current job market, focusing specifically on data scientist roles! This project was created out of a desire to navigate and understand the job market more effectively. It dives into the top-paying and most in-demand skills to help find optimal job opportunities for data analysis.

The data is sourced from Luke Barousse's Python Course which provides the foundation for my analysis, containing detailed information on job titles, salaries, locations, and essential skills. Through a series of python scripts, I explore key questions such as the most demanded skills, salary trends, and the intersection of demand and salary for data scientist roles.

## QUESTIONS

Below are the questions I look to answer in my project:

1. What are the skills most in-demand for the top 3 most popular data roles?
2. How are in-demand skills trending for data scientists?
3. How well do jobs and skills pay for data scientists?
4. What are the optimal skills for data scientists to learn? (Skills with both high demand AND high pay)

## TOOLS I USED

For my deep dive into the data scientist job market, I harnessed the power of several key tools:

1. Python - The backbone of my analysis, allowing me to analyze the data for insights
   - Pandas Library (used to analyze data)
   - Matplotlib Library (used to visualize data)
   - Seaborn Library (used to customize visualizations)
2. Jupyter Notebooks - The tool used to run python scripts, allowing me to include notes and analysis
3. Visual Studio Code - The enviroment for executing python scripts
4. Git and GitHub - essential for version control and sharing my python code and analysis, allowing for collaboration and project tracking

## DATA PREPARATION AND CLEANUP

This section outlines the steps taken to prepare the data for analysis in order to ensure accuracy and usability.

1. Import and clean up data
   - I started by importing the necessary libraries and loading the dataset, followed by initial data cleaning tasks to ensure data quality


## THE ANALYSIS

Each Jupyter notebook for this project aimed at investigating specific aspects of the data job market. Here's how I approached each question:

### 1. What are the most demanded skills for the top three most popular data roles?
   - To find the most demanded skills for the top three most popular data roles, I filtered the positions by which ones were most popular and got the top five skills for these top three roles. This query highlights the most popular job titles and their top skills, showing which skills I should pay attention to depending on the role I'm targeting.
   - View my notebook with detailed steps in the 3.2_Skills_Count.ipynb section!

Data Visualization:  

<img width="365" height="124" alt="image" src="https://github.com/user-attachments/assets/e8e8d5d2-d4e5-44cf-9aff-7219d0657974" />


Results:

<img width="328" height="241" alt="image" src="https://github.com/user-attachments/assets/57306941-d73d-4704-bc28-a2ba2926b6a5" />

Insights:

   - SQL ia the most requested skill for data analysts and data engineers, being in over half the job postings for both roles. Python is the most sought-after skill for data scientists, appearing in 72% of job postings.
   - Data engineers require more specialized technical skills (AWS, Azure, Spark) compared to data analysts and scientists who are expected to be proficient in more general data management and analysis tools (Excel, Tableau).
   - Python is a versatile skill highly demanded across all three roles, but especially within data scientist and engineer roles.

### 2. How are in-demand skills trending for data scientists?
   - To find how skills are trending for data scientists, I filtered data scientists positions and grouped the skills by the month of the job posting. This got me the top five skills of data scientists by month, showing how popular certain skills were
   - View my notebook with detailed steps in the 3.3_Skills_Trend.ipynb section!

Data Visualization:

<img width="430" height="104" alt="image" src="https://github.com/user-attachments/assets/c5ccc3b5-c773-421b-b646-5c7c6787ac82" />


Results:

<img width="622" height="454" alt="image" src="https://github.com/user-attachments/assets/7e8c5fd9-96ff-4fb4-99f5-bf45d32aa802" />

Insights:

   - Python remains the most consistantly demanded skill throughout the year, with slight dips in MArch and September
   - SQL and R both remain constant throughout the year, yet both experience a decrease in demand from August to September
   - The demand for SAS and Tableau seems to be neck and neck from month to month, with only Tableau experiencing the same September dip as the other skills
