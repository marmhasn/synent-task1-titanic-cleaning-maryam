# Titanic Data Cleaning & Preprocessing

## Problem Statement

Raw datasets often contain missing values, inconsistent data types, duplicate records, and poorly structured columns that can affect analysis and machine learning performance. The objective of this project is to clean and preprocess the Titanic dataset to make it suitable for further analysis.

## Dataset Details

* Dataset: Titanic Dataset
* Source: Kaggle
* Format: CSV
* Features include passenger information such as PassengerId, Pclass, Name, Sex, Age, Fare, Embarked, and Survival status.

## Approach

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined the dataset structure and column information.

### 2. Data Inspection

* Checked dataset dimensions, data types, and summary statistics.
* Identified missing values and duplicate records.

### 3. Data Cleaning

* Handled missing values using appropriate techniques such as median and mode imputation.
* Removed duplicate records.
* Converted columns to suitable data types.
* Renamed columns for better readability and consistency.

### 4. Data Export

* Saved the cleaned dataset as a new CSV file for future analysis.

## Results

* Missing values were successfully handled.
* Duplicate records were removed.
* Data types were standardized.
* Column names were improved for readability.
* Generated a clean and structured dataset ready for Exploratory Data Analysis (EDA) and Machine Learning applications.

## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Output

* Cleaned Dataset: `titanic_cleaned.csv`
* Project Notebook: `Titanic_Data_Cleaning_Preprocessing.ipynb`


