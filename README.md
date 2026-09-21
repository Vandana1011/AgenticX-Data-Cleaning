# AgenticX AI – Data Science & Analytics Internship

This repository contains my work for the **AgenticX AI Data Science & Analytics Internship**.

## Task 1 – Real-World Data Cleaning Pipeline

For Task 1, I worked with a messy customer dataset and cleaned it using Python and Pandas.

### What I worked on

- Inspected the dataset and identified data quality issues
- Handled missing values
- Standardized inconsistent values
- Handled invalid numerical values
- Converted dates into the required format
- Validated email and phone number fields
- Removed duplicate records
- Checked numerical data for outliers
- Performed final data validation
- Exported the cleaned dataset

### Final result

- Final dataset: **9,983 rows × 12 columns**
- Duplicate records after cleaning: **0**

### Tools used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Task 2 – Exploratory Analysis with a Finding

For Task 2, I explored the cleaned customer dataset to understand its patterns and identify something interesting that was not obvious at first.

### What I worked on

- Checked the structure of the cleaned dataset
- Checked missing values
- Used basic statistical analysis
- Compared purchase amounts across different groups
- Explored customer distribution by city and country
- Created age groups
- Investigated an unusual pattern in the Age column
- Created a visualization to compare the finding

### Finding

During the analysis, I noticed that the age **43** appeared much more frequently in the cleaned dataset than expected.

- Age 43 before cleaning: **55 records**
- Age 43 after cleaning: **7,573 records**

This showed that the cleaning process created a large concentration around the median age. It helped me understand that data cleaning decisions can affect the patterns we see in a dataset.

### Tools used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Files in this Repository

- `AgenticX_Data_Cleaning.ipynb` – Task 1 data cleaning work
- `Exploratory Analysis.ipynb` – Task 2 exploratory analysis
- `messy_customer_data.csv` – Original dataset
- `cleaned_customer_data_final.csv` – Final cleaned dataset
- `cleaned_customer_data.csv` – Cleaned dataset
- `.gitignore`

## What I Learned

These tasks helped me understand the importance of checking data carefully before analysis and how data cleaning and preprocessing can affect the results of exploratory analysis.
