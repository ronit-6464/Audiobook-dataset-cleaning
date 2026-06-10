# Audiobook-dataset-cleaning
Data cleaning and preprocessing of an Audible audiobook dataset using Python and Pandas. Includes handling missing values, encoding issues, data type conversions, regex-based feature extraction, and dataset standardization.
# Audible Dataset Cleaning Project

## Objective
Clean and standardize an Audible audiobook dataset.

## Dataset Source

https://www.kaggle.com/datasets/snehangsude/audible-dataset

## Data Quality Issues Found
- Encoding issues (\xa0)
- Inconsistent author formatting
- Mixed rating formats
- Price stored as text
- Duration stored as text
- Duplicate records

## Cleaning Steps
1. Renamed columns
2. Fixed encoding issues
3. Standardized whitespace
4. Extracted ratings
5. Converted price to numeric
6. Extracted hours and minutes
7. Removed duplicates

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Output
Cleaned dataset exported to Cexcel.
