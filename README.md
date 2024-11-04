
# Analysis of Education Data in Egypt

## Introduction
This project aims to analyze education data in Egypt using a dataset available on Kaggle. After downloading the data, I cleaned it, added new columns and calculations, and then created Pivot Tables and a Dashboard in Excel to visualize the findings.

## Dataset
- **Source**: [Kaggle - education-in-egypt] ( https://www.kaggle.com/datasets/mohamedalabasy/education-in-egypt )
- **Description**: This dataset contains information about 50,000 students in Egypt, including their personal details, parental education levels, type of education, and grades in various subjects.
## Analysis Steps

1. Data Cleaning
In the data cleaning phase, the following steps were performed to prepare the dataset for analysis:

Handling Missing Values: Ensured no missing values that could affect analysis remained in the dataset.
Added Age Group Column: Created an "Age Group" column to categorize students by age ranges (e.g., 14-16, 17-19) for easier analysis based on age demographics.

2. New Columns and Calculations
The following columns were added to enhance data analysis:

Total Degree: This column represents the sum of scores across all subjects for each student, providing insight into overall performance.
Total Percentage: Shows the percentage of scores achieved out of the possible total, giving a clearer view of individual performance.
Classification: This column categorizes students based on their performance percentage, with labels like "Excellent," "Very Good," "Good".

3. Key Analyses and Findings
3.1 Academic Performance by Education Type
Question: How does student performance vary by education type?
Method: Created a Pivot Table to find the average Total Degree and Total Percentage for each education type. Results were visualized using a bar chart to highlight differences.
3.2 Impact of Parental Education on Student Performance
Question: Is there a relationship between parental education levels and student performance?
Method: Segmented students by parental education levels using the "Father Degree" and "Mother Degree" columns, then calculated the average Total Degree and Total Percentage for each group.
3.3 Age Group Distribution and Performance
Question: How does performance vary across different age groups?
Method: Grouped students by age using the "Age Group" column, and calculated the average Total Percentage within each group. A line chart was used to display performance trends across age groups.
3.4 Analysis of Subject Scores
Question: Which subjects have the highest and lowest average scores?
Method: Calculated the average score for each subject (from Subject_1 to Subject_10), and used a coulmn chart to show the performance levels, highlighting challenging subjects.
4. Dashboard Summary
The Excel dashboard includes the following visuals:

Performance by Education Type: A bar chart summarizing average scores by education type.
Parental Education Impact: A coulmn chart showing average scores for different levels of parental education.
Student Distribution by Academic Classification: A bie chart indicating Classification for student.
Academic Performance by School Year: A area chart showing performance  across shcool years.
Age Group Performance : A bar chart indicating performance trends across age groups.
Subject-Wise Performance: A coulmn chart illustrating the average scores across subjects.

**Data Visualization**:
   - Used bar charts,coulmn chart, line graphs and pie charts to visualize sales trends and category distributions.

 ## How to Access the Project
You can access the project file directly from this repository, including the `egypt_education_dataset.xlsx` file and the visualizations created.