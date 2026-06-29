# Data_Cleaning
## Task 1: Data cleaning and preprocessing using mymoviedb dataset 

##Objective:
The objective of this task was to clean and preprocess a raw dataset by identifying and handling common data quality issues such as missing values, duplicate records, inconsistent column names, and incorrect data types.

##Dataset used:
MyMovieDB Dataset from Kaggle

##Tools Used:
1)Google Colab
2)Python
3)Pandas

##Data Cleaning Steps Performed
1) Loaded the dataset into Pandas.
2) Checked for missing values using `isnull()`.
3) Checked for duplicate records using `duplicated()`.
4) Removed duplicate rows using `drop_duplicates()`.
5) Standardized column names by converting them to lowercase and replacing spaces with underscores.
6) Converted the `release_date` column to datetime format.
7) Verified data types and dataset structure using `info()` and `dtypes`.
8) Exported the cleaned dataset as `mymoviedb_cleaned.csv`.

## Files Included
1) `mymoviedb(1).csv` : Original dataset
2) `mymoviedb_cleaned.csv` : Cleaned dataset
3) `mymoviedb.ipynb.ipynb` : Google Colab notebook containing the code
4) `README.md` : Project documentation

## Outcome
The dataset was successfully cleaned and prepared for further analysis and visualization. Data quality was improved by removing duplicate records, standardizing column names, and converting date fields into the correct format.
