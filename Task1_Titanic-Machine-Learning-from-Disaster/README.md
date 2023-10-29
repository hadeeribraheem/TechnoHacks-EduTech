This README.md file provides an overview of the steps involved in performing data cleaning for the "Titanic - Machine Learning from Disaster" dataset. 
The goal of this task is to handle missing values and outliers in the dataset to ensure the data is suitable for further analysis and modeling.

## Dataset Description

The "Titanic - Machine Learning from Disaster" dataset is a popular dataset available on Kaggle. It contains information about passengers aboard the Titanic, including their demographic details, cabin information, ticket fare, and survival status.

## Task Overview

The task of data cleaning involves addressing missing values and outliers in the dataset. Missing values can occur when data is not recorded or is incomplete, while outliers are extreme values that deviate significantly from the rest of the data. Cleaning the data ensures that missing values are appropriately handled and outliers are either corrected or removed.

## Steps for Data Cleaning

1. **Identify Missing Values**: The first step is to identify the missing values in the dataset. Missing values can be represented in various forms, such as NaN, NULL, or empty cells. It is important to understand the extent and pattern of missing values in different columns.
2. **Handle Missing Values**: There are several strategies for handling missing values, including:"Used Both"
   - **Deletion**: Remove rows or columns with a high percentage of missing values if they do not significantly contribute to the analysis.
   - **Imputation**: Fill in missing values with appropriate substitutes, such as mean, median, mode, or using more advanced imputation techniques like regression or machine learning models.
3. **Identify Outliers**: Outliers are extreme values that deviate significantly from the rest of the data. They can affect the analysis and modeling process. Identify columns that may contain outliers and understand their impact on the dataset.
4. **Handle Outliers**: There are several strategies for handling outliers, including:
   - **Correction**: Correct the outliers if they are due to data entry errors or measurement errors.
   - **Capping**: Cap the extreme values by replacing them with a predefined threshold value.
   - **Removal**: Remove the outliers if they are not representative of the underlying data distribution or if they significantly affect the analysis."Used technique by using interquartile range (IQR)"
