# Tableau
## Salary Analysis Dashboard for Global Data Professionals
## Why Tableau?
Tableau's drag-and-drop interface, built-in geospatial mapping, and robust interactivity options make it an excellent tool for crafting a professional and engaging dashboard like this one.
This Tableau dashboard provides a comprehensive analysis of global salaries for data professionals, segmented by experience level, employment type, job title, country, and company size. The visuals are designed to give quick insights and detailed trends for informed decision-making. Here’s a breakdown of each component:

## 1. Scatter Plot: Average Salary by Experience Level and Employment Type
Purpose:
To show how salaries vary by experience level (Entry Level, Intermediate, Senior) and employment type (Contract, Freelance, Full-Time, Part-Time).

Insights:

Senior professionals across all employment types earn the highest salaries.
Contract and freelance roles show wider salary ranges compared to full-time and part-time roles.
Entry-level professionals have the lowest salaries, but there are exceptions in some contracts.
## 2. Pie Chart: Total Companies by Size and Location
Purpose:
To display the percentage of companies categorized by size (Small, Medium, Large).

Insights:

Medium-sized companies dominate the landscape, hiring 53.71% of employees.
Large companies are next, with 32.62%, while small companies contribute 13.67%.
## 3. Pie Chart: Experience Level
Purpose:
To visualize the distribution of professionals based on their experience levels (Entry Level, Intermediate, Senior).

Insights:

Senior-level professionals make up the largest share (46.13%).
Intermediate-level employees account for 35.09%, followed by Entry-level (14.5%).
Experienced professionals (neither entry nor senior) are the smallest group at 4.28%.
## 4. Bar Chart: Top 10 Employee Residence
Purpose:
To show the top 10 countries where data professionals reside, based on the number of employees.

Insights:

United States leads with 332 employees, highlighting its dominance in hiring for data roles.
Other prominent countries include United Kingdom (44 employees), India (30 employees), and Canada (29 employees).
European countries like Germany (25 employees) and France (18 employees) also contribute significantly.
## 5. Map: Average Salary by Country
Purpose:
To provide a global overview of salary trends, using a heatmap to show average salaries for data professionals by country.

Insights:

Darker regions (e.g., the US, Switzerland, and Germany) indicate higher average salaries.
Lighter regions represent countries with lower average salaries.
Western Europe and North America dominate in terms of higher pay.
## 6. Employment Type Breakdown
Purpose:
To highlight the distribution of employees across different employment types (Full-Time, Freelance, Contract, Part-Time).

Insights:

Full-Time roles dominate, making up the majority.
Freelance and part-time roles represent a smaller fraction, showing their niche appeal.
## 7. Detailed Table: Average Salary by Job Title and Experience Level
Purpose:
To show specific job roles (AI Scientist, BI Data Analyst, etc.) and their respective salaries based on experience levels.

Insights:

For example:
AI Scientists at the senior level earn significantly higher salaries than at the entry or intermediate levels.
BI Data Analysts with experience earn competitive salaries compared to entry-level ones.
Provides a benchmarking tool for professionals and recruiters.
## Key Interactivity Features
Filters:
Dropdown filters for Company Location and Job Title allow users to focus on specific countries or roles.
Hover Tooltips:
Hovering over any visual displays detailed information (e.g., exact salary figures or percentage distributions).
Dynamic Map:
The heatmap updates dynamically when filters are applied, providing tailored geographic insights.
## Conclusion
This Tableau dashboard is a powerful tool for exploring global salary trends for data professionals. It enables:

Job Seekers to benchmark their salaries by role, experience, and location.
Recruiters to identify competitive salary ranges for hiring.
Companies to understand geographic and experience-level trends in the talent market.
By combining interactivity, insightful visuals, and clear storytelling, the dashboard serves as an essential resource for data-driven decision-making in the job market.

## Steps Involved in Creating This Tableau Dashboard
## 1. Data Preparation
Source Data: Import a dataset containing columns like Job Title, Experience Level, Employment Type, Salary (USD), Country, Company Size, and Location.
Data Cleaning:
Use Excel or Python to clean data by handling null values, normalizing salary figures, and ensuring consistent job title naming.
Convert all salary figures to a uniform currency (USD) for analysis.
Formatting: Create calculated fields in Tableau for derived metrics like average salary, employee count, and percentages.
## 2. Building the Dashboard
Connect Data to Tableau

Load the cleaned data into Tableau via an Excel file, database, or CSV.
Ensure proper joins or relationships if using multiple datasets.
Create Worksheets for Key Insights

Scatter Plot: Salary by Experience Level and Employment Type
Use Salary (USD) on the y-axis and Experience Level combined with Employment Type on the x-axis.
Add bubble sizes or colors to indicate different metrics (e.g., job title popularity).
Pie Charts for Experience Levels and Company Sizes
Use COUNTD(Employee ID) or similar measures to show distribution percentages.
Bar Chart: Top 10 Employee Residence
Filter the dataset to show only the top 10 countries by employee count.
Sort data for clarity.
Map: Salary by Country
Use Country as the geographic field and average salary for the gradient.
Leverage Tableau’s built-in mapping capabilities to create an interactive heatmap.
Detailed Table: Salary by Job Title
Create a text table showing Job Title, Experience Level, and Average Salary.
## 3. Design and Layout
Create a Dashboard Layout:

Use Tableau’s dashboard interface to combine the worksheets into a single dashboard.
Arrange visuals in a logical flow:
Start with overall stats (scatter plot, pie charts).
Highlight specific insights (bar chart, map).
Provide detailed breakdowns (table).
Interactivity:

Add filters for Company Location, Job Title, or Experience Level.
Use interactive tooltips to display additional information, such as salary range or employee count, when hovering over data points.
Styling:

Use a dark theme for a professional look.
Maintain consistent font sizes, colors, and legends.
Customize map colors with a gradient to highlight high and low salaries effectively.
## Key Visuals and Their Insights
Scatter Plot:

Shows salary variations by experience level and employment type.
Senior-level professionals in contract roles earn the most.
Pie Charts:

Experience Level: Most employees are senior-level professionals (46.13%).
Company Size: Medium-sized companies (53.71%) dominate the hiring landscape.
Bar Chart:

Highlights the top 10 countries with the most employees (e.g., US, GB, IN).
The US leads with a significant margin (332 employees).
Map:

Visualizes salary disparities globally.
Countries like the US and Western Europe have higher average salaries, while others remain competitive.
Table:

Lists job titles with corresponding experience levels and salaries, making it easy to benchmark.
## Skills Required
Data Cleaning (e.g., Excel, SQL, Python)
Tableau Visualizations (Scatter, Pie, Map, etc.)
Tableau Calculated Fields (for KPIs and metrics)
Dashboard Design (interactivity, filters)
Data Storytelling (insights and trends)





