# Midterm Lab Task 2 – Data Cleaning and Transformation Using Power Query Editor
You are provided with the Uncleaned_DS_jobs.csv dataset (sourced from Kaggle). The objective is to clean and transform this dataset using Power Query Editor in Excel to extract meaningful insights.

## Step 1 – Data Cleaning
Load the Dataset

Import the raw CSV file into Excel using Power Query Editor.

Adjust Layout

Resize column widths and row heights to display data properly.

Remove Extra Spaces

Use the Trim function to eliminate leading and trailing spaces from text fields.

Handle Missing Values

Remove rows containing null or missing values.

Eliminate Duplicates

Remove any duplicate rows to ensure data consistency.

## Step 2 – Data Transformation
Clean the Salary Estimate Column

Select the Salary Estimate column.

Use:
Transform > Extract > Text Before Delimiter
to remove any content after the opening parenthesis (.

Create Min Salary and Max Salary Columns

Go to:
Add Column > Column from Examples
to extract minimum and maximum salary values from the cleaned Salary Estimate column.

Add a Role Type Classification Column

Use:
Add Column > Custom Column
to categorize job titles into roles like Data Scientist, Data Analyst, Data Engineer, etc.

Split the Location Column

Select the Location column.

Use:
Transform > Split Column by Delimiter
(using a comma ,) to divide it into separate components (e.g., City and State).

Standardize Location Names

Create a custom column to replace full state names with their abbreviations, such as:

"New Jersey" → "NJ"

"California" → "CA"

Filter Out Invalid Data

Remove rows with negative values in the Competitors and Industry columns.

Clean the Company Name Column

Use:
Transform > Replace Values or Remove Text
to eliminate unnecessary characters or strings (e.g., ratings, symbols) from company names.

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
