# Elevate_Labs_Task_2

Internship Task 2: Titanic Dataset Analysis
Project Description
This project involves an exploratory data analysis (EDA) of the Titanic dataset. The goal is to understand the dataset's structure, perform data cleaning by handling missing values, and calculate key statistical measures for the different features.

Technologies Used
Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For data visualization.

Seaborn: For statistical data visualization.

Dataset
The analysis is performed on the "Titanic-Dataset.csv" file.

Analysis Overview
Data Loading and Inspection: The dataset is loaded into a pandas DataFrame, and the first few rows are displayed to understand its structure.

Descriptive Statistics: The describe() method is used to generate descriptive statistics for the numerical columns, providing insights into the distribution of data such as count, mean, standard deviation, and quartiles.

Missing Value Handling: A loop iterates through the columns to fill in missing values. Numerical columns are filled with their mean, while categorical/object columns are filled with their mode.

Statistical Calculations: Key statistical measures such as mean, median, mode, variance, and standard deviation are calculated for specific columns, as demonstrated for the 'Age' column.
