# Data Engineering Coding Assessment

## Task
Using Pyspark and Python libraries, I was expected to demonstrate following technical abilities:

**Data Exploration**
1. Provide a detailed analysis of source data: Column values (eg: Numerical vs character), categorical columns, etc.
2. List of KPIs to be resolved:
   - Whats the number of jobs posting per category (Top 10)?
   - Whats the salary distribution per job category?
   - Is there any correlation between the higher degree and the salary?
   - Whats the job posting having the highest salary per agency?
   - Whats the job positings average salary per agency for the last 2 years?
   - What are the highest paid skills in the US market?
   
**Data Processing**
1. Create functions to process your dataset (Cleaning, column pre-processing, data wrangling, transformation etc)
2. Apply atleast 3 feature engineering techniques
3. Features removal based on the exploration/ profiling.

## The Solution
My solution is divided into following sections:

1. **Data Preprocessing**
   - Data cleaning
   - Removing duplicate rows
   - Missing value analysis
     - Removing columns based on > 90% missing values
2. **Analysis**
   - Converting columns to appropriate types ( Numerical, Categorical and String type)
   - Basic Summary for columns of each data types
   - Frequency distribution for Categorical columns
   - Unique value analysis
3. **Feature Engineering**
   - Normalization of Salary columns
   - Qualification and Preferred skills Analysis
   - Minimum Degree Requirement Analysis
4. **KPIs**
   - What is the number of job postings per category?
   - What is the salary distribution per job category?
   - Is there a correlation between the higher degree and salary?
   - Whats the job posting having the highest salary per agency?
   - Whats the job positings average salary per agency for the last 2 years?
   - What are the highest paid skills in the US market?
5. **Test Cases**

**Thanks for going through the analysis**
