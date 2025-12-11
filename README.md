# sales_cleaning_data

# Data Cleaning Project (Python + Jupyter Lab)

This project shows my complete data cleaning workflow using Python and Jupyter Lab.  
The goal is to transform raw data into a clean, structured, and analysis-ready dataset.

---

## Project Overview

This notebook includes:
- Loading raw data
- Inspecting missing values
- Handling nulls (group-based filling, median, etc.)
- Detecting and treating outliers
- Standardizing column names and formats
- Converting data types
- Creating new calculated fields
- Exporting cleaned data for analysis

## Technologies Used

- Python 3
- Jupyter Lab / Jupyter Notebook
- pandas
- numpy
- matplotlib

## Key Cleaning Techniques

The notebook demonstrates techniques such as:

- Filling missing values with:
  - group median  
  - global mean/median  
  - logical replacements  
- Detecting outliers using:
  - IQR method  
  - visual inspection (boxplot, histogram)  
- Removing meaningless data points
- Fixing inconsistent formatting  
- Parsing dates correctly  
- Standardizing categorical values  
- Saving cleaned dataset as CSV

## How to Run the Notebook

1. Clone the repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
