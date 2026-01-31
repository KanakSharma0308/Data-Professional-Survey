# Data-Professional-Survey
This project is an end-to-end Power BI analysis of a real-world survey conducted with over 600+ Data Professionals. The dataset includes insights into job titles, average salaries, programming language preferences, and workplace happiness. The challenge of this project was transforming "messy" survey responses into a clean, structured dashboard for industry benchmarking.

🖼️ Dashboard Preview


🚀 Key Objectives
1. Salary Benchmarking: Analyze average salaries across different roles (Data Analyst, Scientist, Engineer, etc.).
2. Tech Stack Popularity: Identify the most preferred programming languages in the current market.
3. Geographic Insights: Compare professional trends across countries like the USA, India, UK, and Canada.
4. Satisfaction Metrics: Measure work-life balance and salary satisfaction levels.

🛠️ Technical Workflow
1. Advanced Data Transformation (Power Query)
Survey data is notoriously messy. I performed extensive cleaning steps:
Text Standardization: Split and cleaned columns with "Other" responses to group similar job titles and programming languages.
Salary Normalization: Transformed salary ranges (e.g., "$100k-$125k") into numeric averages to allow for mathematical calculations.
Data Filtering: Removed non-essential metadata and handled inconsistent survey entries.
Attribute Splitting: Used delimiters to extract clean values from complex string responses.

2. Data Visualization & UI Design
KPI Cards: Displaying the total number of survey participants and their average age.
Stacked Bar Chart: Comparing average salaries by specific job titles.
Clustered Column Chart: Visualizing the popularity of languages like Python, R, and SQL.
Tree Map: An interactive country-based filter to analyze regional differences.
Gauge Charts: Measuring qualitative metrics like Work-Life Balance and Salary Satisfaction scores.
Donut Chart: Analyzing salary distribution by gender.

💡 Key Insights
The Python Dominance: The data clearly shows Python as the top language among data professionals globally.
Regional Disparity: The interactive Tree Map reveals significant salary variations between different geographic regions for the same job titles.
Happiness vs. Pay: Using Gauge charts, I correlated salary satisfaction with overall work-life balance, providing a holistic view of the profession.
