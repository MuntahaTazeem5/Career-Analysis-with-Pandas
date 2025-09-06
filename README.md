
**📊 Career Analysis with Pandas**

**📝 Problem Statement**

Choosing the right career requires analyzing multiple factors like salary, education requirements, work-life balance, and growth outlook. In this project, we use Pandas DataFrame to organize and analyze 10 career options.

The goal is to apply data manipulation techniques (adding new columns, sorting, filtering) to gain insights into the most promising careers.

**📂 Dataset Description**

The dataset includes 10 careers with the following columns:

-Column	Description	Example
-Career	Name of the career	Data Scientist
-Average_Salary_$	Average yearly salary in USD	120000
-Education_Years	Years of formal education required	6
-Work_Life_Balance_10	Work-life balance rating (1–10)	7
-Growth_Outlook_%	Expected industry growth in %	15

**🛠️ Tasks**
1. Create a DataFrame:

Use pandas.DataFrame() to create the dataset with 10 rows and 5 columns.

2. Add a New Column:

Salary_per_EduYear=Average_Salary/Education_Years
​
Helps measure salary efficiency per year of education.

3. Sort Careers:

Sort the DataFrame by Average_Salary_$ (descending) to see the top-paying jobs first.

4. Filter Careers:

Select careers with:

Growth_Outlook_% > 15

Work_Life_Balance_10 >= 7

This gives careers that are both promising and balanced.

**📈 Expected Insights**

Which careers pay the most

Which careers require fewer years of education for higher salaries

Which careers combine growth + balance

**Learning Outcomes**

By completing this project, you will learn how to:

Create a DataFrame in Pandas

Add computed columns

Sort and filter data effectively

Extract real-world insights from raw data

