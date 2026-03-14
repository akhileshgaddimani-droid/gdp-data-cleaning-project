# GDP-Data-Cleaning

## Overview
This project focuses on cleaning and preparing a messy GDP dataset using Python and Pandas.
Real-world datasets often contain issues such as missing values, inconsistent formatting, incorrect data types, and duplicate records. The objective of this project is to clean the dataset and transform it into a structured format that is ready for analysis.

The dataset contains GDP values of different countries across multiple years. However, the raw data includes several data quality issues that need to be addressed before performing any analysis.

This project demonstrates essential data cleaning and preprocessing skills required for data analysts and data scientists.

## Dataset
The dataset used in this project contains GDP values for different countries over several years.

## Columns

- Country – Name of the country
- Year – Year of the GDP record
- GDP_Value – GDP value of the country

## Issues Found in Dataset
The dataset contains several real-world data problems:

- Missing values in the GDP column
- Inconsistent country names (uppercase/lowercase, extra spaces)
- GDP values stored as strings with commas
- Duplicate rows
- Extra spaces in column names
- Incorrect data types

## Tools and Technologies Used
- Python
- Pandas
- Jupyter Notebook
- CSV Dataset

## Project Workflow
## 1. Data Loading
The dataset was loaded using the Pandas library and inspected to understand its structure.

## 2. Data Inspection
Initial exploration was performed to check:

**Column names**

- Data types
- Missing values
- Duplicate rows

## 3. Handling Missing Values

Missing values in the GDP column were identified and handled appropriately to ensure data consistency.

## 4. Fixing Formatting Issues
Column names were cleaned by removing extra spaces and converting them into lowercase for consistency.

Country names were standardized to maintain uniform formatting.

**Example:**

- " india " → India
- "USA" → United States
- "CHINA" → China
- "germany" → Germany

## 5. Data Type Conversion

The GDP values were originally stored as strings with commas. These values were cleaned and converted into numeric format (float) for analysis.

The year column was converted into integer format.

## 6. Removing Duplicate Records

Duplicate rows were identified and removed to ensure each record represents unique data.

## 7. Data Validation

After cleaning, the dataset was checked to ensure:

- No missing values remain
- Correct data types are assigned
- Consistent formatting across the dataset

## 8. Sorting and Saving the Data

The final dataset was sorted by country and year and saved as a new cleaned dataset file.

## Results

After performing the data cleaning process:

- Missing values were handled
- Country names were standardized
- GDP values were converted to numeric format
- Duplicate records were removed
- Dataset was sorted and structured properly

The cleaned dataset is now ready for data analysis, visualization, and economic trend analysis.

## Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Handling Missing Values
- Data Type Conversion
- Removing Duplicates
- Data Standardization
- Pandas Data Manipulation
