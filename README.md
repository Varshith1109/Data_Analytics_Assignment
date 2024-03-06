### Code Documentation

This document provides a brief overview of the Python code provided. The code is aimed at data manipulation and transformation tasks using the pandas library in Python.

---

#### 1. Import Required Libraries

import pandas as pd
from collections import defaultdict
import numpy as np

#### 2. Load Data

df = pd.read_csv("/Users/varshithkumarnaraboina/Desktop/input.csv")


#### 3. Data Preprocessing
- Extracting columns and converting date columns to datetime.
- Filling missing values in the 'Date of Exit' column.
- Reordering columns for pattern consistency.

#### 4. Data Transformation and Sorting
- Iterating through each row to extract dates and corresponding column names.
- Sorting the extracted dates and column names.

#### 5. Generating DataFrame for HR Records
- Creating DataFrame to record employee HR data based on date intervals.
- Handling compensation, review, and engagement data.

#### 6. Adding Last Compensation and Pay Raise Date
Calculating the last compensation and pay raise date for each employee.
-   Note: Ensure to run this cell twice for correct execution due to dependency issues.

#### 7. Final Data Processing
- Finalizing the DataFrame for output.
- Converting float columns to integer and replacing zeros with empty cells.
- Converting 'Review' column to string, removing decimals, and renaming it to 'Performance Rating'.

#### 8. Output
- Writing the processed DataFrame to a CSV file named 'final_output_file.csv'.

---

This documentation outlines the main functionalities and transformations performed by the provided Python code.
