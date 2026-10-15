# Baseball Salary Analysis with Databricks, PySpark, and Spark SQL

## Project Overview

This project analyzes professional baseball salary data from 2003 using Databricks, PySpark, and Spark SQL.

The dataset, `baseball_salaries_2003v2.txt`, contains player salary information including team, player name, salary, and position. The project involved importing the raw text file into Databricks, cleaning and transforming the data, creating a structured DataFrame, and answering a series of analytical questions using both Spark SQL and PySpark DataFrame operations.

## Tools and Technologies

- Databricks
- PySpark
- Apache Spark
- Spark SQL
- Python
- DataFrames
- Data Cleaning
- Data Transformation
- Data Analysis

## Dataset

The dataset contains salary information for professional baseball players from the 2003 season.

The final DataFrame included the following columns:

- `Team`
- `Player`
- `Salary`
- `Position`

The analysis was performed on 381 player records.

## Data Preparation

The raw text file required several preprocessing steps before analysis.

I used PySpark to:

- Load the text file into Databricks
- Remove the header row from the dataset
- Rename columns
- Trim unnecessary whitespace
- Clean player names
- Convert salary values into integer format
- Prepare the DataFrame for SQL and PySpark analysis

## Analysis Performed

The project included seven analysis tasks using both Spark SQL and PySpark DataFrame functions.

Key tasks included:

1. Creating and cleaning the baseball salary DataFrame.
2. Creating a `baseball_salaries` table for SQL analysis.
3. Identifying the five highest-paid players.
4. Reproducing salary ranking analysis using PySpark DataFrame operations.
5. Identifying the highest-paid First Baseman.
6. Calculating the average salary for each player position.
7. Reproducing position-based salary analysis using PySpark DataFrame operations.

The seven player positions analyzed were:

- Catcher
- First Baseman
- Outfielder
- Pitcher
- Second Baseman
- Shortstop
- Third Baseman

## Key Findings

Some of the main findings from the analysis were:

- Alex Rodriguez was the highest-paid player in the dataset with a salary of approximately **$22 million**.
- Carlos Delgado was the highest-paid First Baseman.
- Outfielders had the highest average salary among the seven positions analyzed, at approximately **$4.05 million**.
- First Basemen had an average salary of approximately **$3.59 million**.
- Shortstops had an average salary of approximately **$2.95 million**.

## Skills Demonstrated

This project demonstrates experience with:

- Working in a Databricks environment
- Processing raw text data with PySpark
- Cleaning and transforming datasets
- Using Spark SQL for data analysis
- Using PySpark DataFrame functions
- Sorting and filtering large datasets
- Grouping and aggregating data
- Comparing SQL and DataFrame-based approaches
- Extracting insights from structured data

## Project Files

- `CIS5560_Lab_Midterm_Exam_1.ipynb` — exported Databricks notebook containing the analysis
- `baseball_salaries_2003v2.txt` — source dataset, if included
- `README.md` — project documentation

## Conclusion

This project gave me hands-on experience using Databricks, PySpark, and Spark SQL to transform raw data into structured information and answer analytical questions. It strengthened my ability to clean data, write distributed queries, perform aggregations, and communicate insights from a real-world dataset.
