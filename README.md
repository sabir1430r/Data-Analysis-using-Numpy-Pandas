# Data-Analysis-using-Numpy-Pandas
Data analysis project using Python, NumPy, and Pandas to explore student performance across subjects, genders, and regions. Includes data cleaning, aggregation, and insights on study hours, scores, and trends to understand factors affecting academic outcomes.

Student Performance Data Analysis using NumPy & Pandas
 Overview

This project analyzes a dataset containing academic performance data of students across different subjects, regions, and genders.
It focuses on data cleaning, aggregation, and exploratory analysis using NumPy and Pandas, demonstrating how to handle missing values, perform group-based insights, and extract trends from small datasets.

 Dataset Information

Dataset Name: Student Evaluation Dataset
Total Records: 20
Columns:

Column	Description
Student_ID	Unique identifier for each student
Name	Name of the student
Subject	Subject of the test (Math, Science, English)
Score	Marks obtained by the student (may include missing values)
Hours_Studied	Number of study hours (may include missing values)
Gender	Gender of the student (M/F)
Region	Region where the student belongs (North, South, East, West)

Dataset Characteristics:

Includes missing values in Score and Hours_Studied

Contains both categorical (Subject, Gender, Region) and numerical (Score, Hours_Studied) data

Ideal for data cleaning, grouping, and analysis tasks

Tools & Libraries

Python 3

NumPy

Pandas

Matplotlib / Seaborn (optional for visualization)

Task 1: Data Cleaning

Identified missing values in Score and Hours_Studied

Replaced missing Score values with the average score of that subject

Replaced missing Hours_Studied with the mean study hours

Dropped rows where both values were missing

Task 3: Subject-wise Analysis

Calculated average score per subject

Found which subject had the highest average score

Identified which subject had maximum average study hours

Determined top performer in each subject

Task 4: Regional Analysis

Calculated average score by region

Found region with highest average study hours

Identified region with lowest performance

Task 5: Gender-Based Analysis

Compared average score of male vs female students

Found which gender studied more hours on average

Listed Top 3 highest-scoring female students

Listed Lowest 2 scoring male students

Task 6: Performance Categorization

Created new column “Performance”

High → Score ≥ 80

Low → Score < 80

Counted number of students in each category

Compared distribution across different subjects

Task 7: Insights & Trends

Analyzed relationship between study hours and scores

Found example of a student who:

Scored above 80 with <10 study hours

Scored below 70 with >12 study hours

Concluded that more study time doesn’t always mean better performance, highlighting individual learning efficiency.

Key Insights

Subject with highest average score: [Fill after running your analysis]

Region with best performance: [Fill after analysis]

Gender with higher study hours: [Fill after analysis]

Study time vs score correlation: Weak/Moderate/Strong (fill with your result)

Future Improvements

Add correlation heatmaps and trendline visualizations

Integrate automated report generation using Pandas Profiling

Expand dataset size for deeper statistical analysis

Mohammad Sabir
Data Analyst | Python | Pandas | NumPy | SQL
