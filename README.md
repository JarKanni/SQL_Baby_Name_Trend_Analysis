# SQL_Baby_Name_Trend_Analysis
SQL Analysis of American Baby Name Trends utilizing ranking, grouping, joining, ordering, CTEs, and pattern matching

# Explanation
[Datacamp project](https://app.datacamp.com/learn/projects/1441) diving into U.S. Social Security Administration baby name data from 1920 to 2020.  The dataset lists year and first names along with the number and sex of babies given the name.  Datacamp cropped the full original dataset down to save space and processing time.

SQL queries used for answering key questions such as _"What were the top-ranked female names since 1920?"_ and _"Which names spent the most years at number one?"_
- Ranked names by Classic or Trendy based on how often it occured over time
- Filtered, grouped, and ordered lists of names based on pattern matching and meeting specific criteria
- Created CTE (common table expression) and joined with main table to further filter data

# Files
#### baby_names_analysis.ipynb
- analyses changing tastes over time
- utilizes SQL queries for ranking, grouping, joining, ordering, CTEs, and pattern matching

#### usa_baby_names.csv
- Columns:
    - year - int
    - first_name - string
    - sex - F/M - bool
    - num - int
- database baby_names_analysis.ipynb uses for SQL queries
- data originally published by U.S. Social Security Administration
    - covers years between 1920 - 2020
- gathered by [datacamp](https://app.datacamp.com/learn/projects/1441)


# Contact Information
Name: Jared R. Kannianen 
<br />
Organization: Masterschool - Data Analyst 
<br />
Email: jarkanni@campus.masterschool.com
