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

<img width="680" height="237" alt="image" src="https://github.com/user-attachments/assets/976c3f91-3b3e-4675-9cba-45f10a17e2f4" />

2. Filter to data scientist jobs in the US
   - For the majority of this project, I filtered the original dataframe to only include data scientist roles within the United States

<img width="718" height="46" alt="image" src="https://github.com/user-attachments/assets/cd490bd5-2337-40d7-86ae-4b84033b3139" />

## THE ANALYSIS

Each Jupyter notebook for this project aimed at investigating specific aspects of the data job market. Here's how I approached each question:

### 1. What are the most demanded skills for the top three most popular data roles?
   - To find the most demanded skills for the top three most popular data roles, I filtered the positions by which ones were most popular and got the top five skills for these top three roles. This query highlights the most popular job titles and their top skills, showing which skills I should pay attention to depending on the role I'm targeting.
   - View my notebook with detailed steps in the 3.2_Skills_Count.ipynb section!

Data Visualization:  

<img width="720" height="236" alt="image" src="https://github.com/user-attachments/assets/5392dd15-0c87-4725-8a53-19112ae08acd" />



Results:

<img width="637" height="483" alt="image" src="https://github.com/user-attachments/assets/faa15f07-fa57-42b3-82ee-3ffbc2e6e88f" />


Insights:

   - SQL ia the most requested skill for data analysts and data engineers, being in over half the job postings for both roles. Python is the most sought-after skill for data scientists, appearing in 72% of job postings.
   - Data engineers require more specialized technical skills (AWS, Azure, Spark) compared to data analysts and scientists who are expected to be proficient in more general data management and analysis tools (Excel, Tableau).
   - Python is a versatile skill highly demanded across all three roles, but especially within data scientist and engineer roles.

### 2. How are in-demand skills trending for data scientists?
   - To find how skills are trending for data scientists, I filtered data scientists positions and grouped the skills by the month of the job posting. This got me the top five skills of data scientists by month, showing how popular certain skills were.
   - View my notebook with detailed steps in the 3.3_Skills_Trend.ipynb section!

Data Visualization:

<img width="430" height="104" alt="image" src="https://github.com/user-attachments/assets/c5ccc3b5-c773-421b-b646-5c7c6787ac82" />


Results:

<img width="622" height="454" alt="image" src="https://github.com/user-attachments/assets/7e8c5fd9-96ff-4fb4-99f5-bf45d32aa802" />

Insights:

   - Python remains the most consistantly demanded skill throughout the year, with slight dips in MArch and September
   - SQL and R both remain constant throughout the year, yet both experience a decrease in demand from August to September
   - The demand for SAS and Tableau seems to be neck and neck from month to month, with only Tableau experiencing the same September dip as the other skills

### 3. How well do jobs and skills pay for data scientists?
   - To identify the highest-paying roles and skills, I only got jobs in the United States and looked at their median salaries. First though, I looekd at the salary distributions of common data jobs like data scientists, data engineers, and data analysts to get an idea of which jobs are paid the most.
   - View my notebook with detailed steps in the 3.4_Salary_Analysis.ipynb section!

Data Visualization:

<img width="689" height="184" alt="image" src="https://github.com/user-attachments/assets/837d097b-9b85-4ef5-9539-f8bea26aad62" />

Results:

<img width="693" height="463" alt="image" src="https://github.com/user-attachments/assets/5d3abd6c-ea0d-4941-9ea6-fc6a71660e81" />

Insights:

   - There's a significant variation in salary ranges netween different job titles. Senior data scientist positions tend to have the highest salary potential, indicating the high value placed on advanced data skills and experience in the industry.
   - Senior data engineer and senior data scientist roles show a considerable number of outliers on the higher side of the salary spectrum, suggesting that exceptional skills or circumstances can lead to high pay in these roles. In contrast, data analyst roles demonstrate more consistency in salary, with fewer outliers.
   - The median salaries increase with the seniority and specialization of the roles. Senior roles for data scientists, data engineers, and data analysts not only have higher median salaries but also larger differences in typical salaries, reflecting greater variance in compensation as responsibility increases.  

Data Visualization:

<img width="888" height="423" alt="image" src="https://github.com/user-attachments/assets/dd6ddf18-703d-429b-befe-1a2439192768" />

Results:

<img width="635" height="469" alt="image" src="https://github.com/user-attachments/assets/9cebc3ab-6c9c-4bde-ad93-de71a36fd864" />

Insights:

   - The top graph shows specialized technical skills like Asana, Airtable, and Watson are associated with higher salaries, some reaching up over $250K, suggesting that advanced technical proficiency can increase earning potential.
   - The bottom graph highlights that foundational programming skills like Python, SQL, and R are the most in-demand, even though they may not offer the highest salaries. This demonstrates the importance of these core skills for employability in data scientist roles.
   - There's a clear distinction between the skills that are highest paid and those that are most in-demand. Data scientists aiming to maximize their career potential should consider developing a diverse skill set that includes both high-paying specialized skills as well as more in-demand, foundational skills.

### 4. What is the most optimal skill to learn for data scientists?

Data Visualization:

<img width="887" height="535" alt="image" src="https://github.com/user-attachments/assets/75d47784-999c-4c76-b0df-96cd5b0d7c9f" />

Results:

<img width="666" height="467" alt="image" src="https://github.com/user-attachments/assets/67ca3587-6c67-4ea3-a376-2c845bef6f2c" />

Insights:

   - The scatter plot shows that most of the programming skills tend to cluster around both higher salary levels and higher likelihood of appearing in data scientist jobs, indicating these as some of the most optimal skills to learn for aspiring data scientists.
   - Libraries (specifically Tensorflow and Hadoop) are on the higher end of salaries, yet appear on the lower end of being required for advertised data scientist roles.
   - Analyst tools like Tableau and Excel, while still important to any data scientist or analytical role, tend to fall on the lower ends of both average salaries and likelihood of being in data scientist roles.

## What I Learned

Through the creation of this project, I have been able to deepen my understanding of the data analytical job market and enhance my technical skills with Python, specifically with data manipulation and visualization. A few specific things I learned include:
   - Advanced Python Usage: Utilizing libraries such as Pandas for data manipulation both matplotlib and Seaborn for data visualization helped me to perform more complex data analysis tasks more efficently.
   - Data Cleaning Importance: I learned that thorough data cleaning and preparation are crucial before any analysis can be conducted, ensuring the accuracy of insights found through the data.
   - Strategic Skill Analysis: This project emphasized the importance of aligning one's technical skills with market demand. Understanding the relationship between skill demand, salary, and job availability allows for more strategic career planning in the tech industry.

## Insights

This project provided several general insights into the data job market for data scientists:
   - Skill Demand and Salary Correlation: There is a clear correlation between the demand for specific skills and the salaries these skills command. Advanced and specialized skills like Python and Tensorflow often lead to higher salaries.
   - Market Trends: There are changing trends in skill demand, highlighting the dynamic nature of the data job market. Keeping up with these trends is essential for career gorwth as a data scientist.
   - Economic Value of Skills: Understanding which skills are both in-demand and well-compensated can guide data scientists in prioritizing learning to maximize their economic returns.

## Challenges I Faced

This project was not without its challenges, but it provided great learning opportunities:

   - Data Inconsistencies: Handling missing or inconsistent data entries requires careful consideration and thorough techniques to ensure the integrity of the analysis.
   - Complex Data Visualizations: Designing effective visual representations of complex datasets was challenging in the sense of conveying insights clearly and compellingly.
   - Balancing Breadth and Depth: Deciding how to deeply dive into each analysis while maintaining a broad overview of the landscape required balancing to ensure comprehensive coverage without getting lost in details.

## Conclusion

This exploration of the data scientist job market has been increadibly informative, highlighting the critical skills and trends that shape this evolving field. The insights I got enhance my understanding and provide actionable guidence for anyone looking to advance their career as a data scientist. As the market continues to change, ongoing analysis will be essential to stay ahead in data analytical jobs. This project is a good foundation for future explorations and underscores the importance of continuous learning and adaptation in the data field.
