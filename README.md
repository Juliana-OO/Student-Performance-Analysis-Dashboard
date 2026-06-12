# Student-Performance-Analysis-Dashboard
Excel dashboard analyzing student performance using data cleaning, pivot tables, KPI metrics and visualization

## Project Overview

This project analyzes how student behaviours and demographics affects their academic performance using excel. The goal was to clean and transform raw student data, perform exploratory analysis and develop an interactive dashboard to uncover trends related to academic achievement, attendance, study habits and performance levels.

The project demonstrates core data analytics skill including data cleaning, data transformation, KPI development, pivot tables, data visualization and dashboard design.

## Business Problem 
Educational instituition often admit large amounts of students data but struggle to convert it into actionable insights.

This project aims to answer key questions such as:

- How are students distributed across performance categories?
- Is there a difference in academic performance acreoss genders?
- Does attendance impact academic performance?
- Do study habits influence student outcomes?
- What proportion of students are performing at an excellent, good, average or poor level?

## Dataset Information

The dataset used in this analysis was obtained from kaggle and it contains student records with attributed including:

- Student ID
- Age
- Gender
- Class
- Study Hour Per Day
- Attendance Percentage
- Math Score
- English Score
- Science Score

Source: https://www.kaggle.com/datasets/suvidyasonawane/student-performance-dataset

## Data Cleaning Process

The folowing data quality checks were performed
- Checked for missing values
- Checked for duplicate records
- Checked for blank rows
- Reviewed formatting consistency
- Validated numerical fields

## Data Transformation

### Average Score

A new column was created to calculate the average academic performance of each student.

Formula:

excel
=(Math Score + English Score + Science Score)/3


### Performance Category

Students were categorized based on their average score using nested IF statements.

 Score Range  Category
------------------------
 90 and above Excellent 
 80 – 89      Good 
 70 – 79      Average
 Below 70     Poor 


## Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

- Total Students
- Average Score
- Highest Score
- Lowest Score

## Pivot Table Analysis

The following analyses were conducted:

### 1. Performance Category Distribution
Counts the number of students in each performance category.

### 2. Average Score by Gender
Compares average academic performance across genders.

### 3. Average Score by Performance Category
Analyzes score distribution across performance groups.

### 4. Attendance vs Average Score
Evaluates the relationship between attendance and academic performance.

### 5. Study Hours vs Average Score
Examines how study habits influence academic outcomes.

## Dashboard Features

The dashboard was built entirely in Microsoft Excel and includes:

- KPI Cards
- Pivot Tables
- Pivot Charts
- Performance Analysis Visualizations
- Interactive Data Summaries

##Tools Used
- Microsoft Excel
- Pivot Table
- Pivot Charts
- Conditional Formatting
- Excel Formulas
- Dashboard Design Techniques

## Skills Demonstrated
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Development
- Business Insight Generation
- Analytical Thinking

## Key Insights
Key Insights generated from this analysis include:

- Students with higher study hours generally achieve higher average score.
- Higher attendance rates were associated with improved academic performance.
- The majority of students were concentrated within the good and avaerage performance categories.
- Gender-based comparison provided additional insight into performance trends.

## Project Files
- Student_Performance_Analysis_Dashboard.xlsx
- Dashboard Screenshots
- Pivot Table Screenshots
- README.md

## Author 
Juliana Owokade

MS Data Science & AI
University of Central Missouri

Data Science | Machine Learning | Artificial Intelligence | Analytics
