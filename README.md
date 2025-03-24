# Netflix Data Cleaning

## Project Overview
This project focuses on cleaning and preprocessing the raw Netflix dataset to ensure it is structured and ready for analysis.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Files Included
- `netflix_raw_data.csv` – The original dataset.
- `netflix_data_cleaning.ipynb` – Jupyter Notebook containing the cleaning steps.


## Steps Performed

### 1. Importing the Dataset
- Loaded the raw dataset using `pandas.read_csv()`.

### 2. Handling Missing Values
- Identified missing values using `df.isnull().sum()`.
- Filled missing values in categorical columns using the mode.
- Dropped records with excessive missing data where necessary.

### 3. Converting Data Types
- Converted date columns to datetime format using `pd.to_datetime()`.

### 4. Removing Duplicates
- Checked for duplicate records using `df.duplicated().sum()`.
- Dropped duplicate records using `df.drop_duplicates()`.

### 5. Standardizing Text Data
- Stripped whitespace and standardized text formats for consistency.

### 6. Exporting Cleaned Data
- Saved the cleaned dataset as `cleaned_netflix_data.csv` using `df.to_csv()`.


## Conclusion
The Netflix dataset has been successfully cleaned, making it suitable for further analysis and visualization.
