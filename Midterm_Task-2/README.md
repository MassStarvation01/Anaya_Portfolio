# Midterm Lab Task 2 – Data Cleaning and Transformation Using Power Query Editor

## STEP 1 – Data Cleaning
Load the Dataset

Import the raw CSV file into Excel using Power Query Editor.

Adjust Layout

Resize column widths and row heights to properly display data.

Remove Extra Spaces

Use the Trim function to eliminate leading and trailing spaces from text fields.

Handle Missing Values

Remove rows containing null or missing values.

Eliminate Duplicates

Remove any duplicate records to ensure data consistency.

## STEP 2 – Data Transformation
Clean the Salary Estimate Column

In Power Query, select the Salary Estimate column.

Use Transform > Extract > Text Before Delimiter to remove content after the opening parenthesis (.

Create Minimum and Maximum Salary Columns

Use Add Column > Column from Examples to extract Min Salary and Max Salary values from the cleaned Salary Estimate column.

Add Role Type Classification

Navigate to Add Column > Custom Column and create a new column to categorize job titles into types such as Data Scientist, Data Analyst, Data Engineer, etc.

Split the Location Column

Select the Location column.

Use Transform > Split Column by Delimiter (comma) to divide it into separate components (e.g., City and State).

Standardize Location Names

Add a Custom Column to update and standardize location values, replacing full state names (e.g., “New Jersey”) with abbreviations (e.g., “NJ”).

Filter Out Invalid Data

Remove entries with negative values in the Competitors and Industry columns.

Clean Company Name Column

Use Transform > Replace Values or Remove Text to eliminate unwanted characters or strings from the Company Name field (e.g., remove ratings or symbols).

## STEP 3 – Screenshots

Before Data Cleaning:
(See screenshot of raw data before any transformations were made.)

<img src="Images/Uncleaned_data.jpg" alt="Alt Text" width="400" height="300"> 

[*Here's the raw file*](https://github.com/NaythanIsME/EDM-Portfolio/blob/main/Midterm%20Task%202/Files/Uncleaned_DS_jobs.xlsx)

After Data Cleaning:
(See screenshot of cleaned data post-transformation.)

<img src="Images/Uncleaned_data.jpg" alt="Alt Text" width="400" height="300"> 

[*Here's the cleaned file*](https://github.com/NaythanIsME/EDM-Portfolio/blob/main/Midterm%20Task%202/Files/NathanielLimiac_task2.xlsx)

## STEP 4 – Final Output Queries
Here are the final queries after performing all necessary data transformations:

Sal By Role Type dup: A query with job titles categorized by role type.

<img src="Images/Sal By Role Type dup.jpg" alt="Alt Text" width="1000" height="300"> 

Sal By Size ref: A query focusing on salary data by company size or another metric.

<img src="Images/Sal By Size ref.jpg" alt="Alt Text" width="1000" height="300"> 

Sal By State ref: A query analyzing salary data by state/location.

<img src="Images/Sal By State ref.jpg" alt="Alt Text" width="1000" height="300"> 

Uncleaned DS Jobs: The original dataset before any transformations.

<img src="Images/Uncleaned DS Jobs.jpg" alt="Alt Text" width="1000" height="300"> 

## Physical Data Model
(Insert physical data model screenshot here)

<img src="Images/Physical Model.jpg" alt="Alt Text" width="400" height="300"> 
