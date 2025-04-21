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

STEP 2 – Data Transformation
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
