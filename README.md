# Customer Personality Data Cleaning and Preprocessing

## Dataset

Customer Personality Analysis Dataset

## Objective

The objective of this project was to clean and preprocess a raw dataset by checking for missing values, duplicate records, inconsistent formats, and data type issues before analysis.

## Tools Used

* Python
* Pandas
* Jupyter Notebook (VS Code)
* GitHub

## Steps Performed

### 1. Dataset Loading

* Imported the dataset using Pandas.
* Loaded the CSV file into a DataFrame.

### 2. Dataset Inspection

* Viewed the first few rows using `df.head()`.
* Inspected dataset structure using `df.info()`.

### 3. Missing Value Analysis

* Checked all columns using `df.isnull().sum()`.
* Result: No missing values were found.

### 4. Duplicate Record Analysis

* Checked duplicate records using `df.duplicated().sum()`.
* Result: No duplicate rows were found.

### 5. Column Name Standardization

* Converted column names to lowercase.
* Replaced spaces with underscores for consistency.

### 6. Date Format Conversion

* Converted the `dt_customer` column to datetime format using Pandas.

### 7. Data Type Verification

* Verified column data types after preprocessing.

### 8. Export Cleaned Dataset

* Saved the processed dataset as `cleaned_data.csv`.

## Results

* Missing Values Found: 0
* Duplicate Records Found: 0
* Column Names Standardized: Yes
* Date Format Standardized: Yes
* Cleaned Dataset Generated: Yes

## Project Structure

task-1-data-cleaning/

├── dataset/

│ ├── raw_data.csv

│ └── cleaned_data.csv

├── screenshots/

│ ├── dataset_preview.png

│ ├── dataset_info.png

│ ├── missing_values.png

│ ├── duplicates_check.png

│ └── cleaned_dataset_saved.png

├── data_cleaning.ipynb

└── README.md

## Conclusion

The dataset was successfully inspected, validated, and preprocessed. The cleaned dataset is ready for further data analysis and visualization tasks.
