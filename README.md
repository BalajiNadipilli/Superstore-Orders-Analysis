# Superstore-Orders-Analysis
This repository contains a Jupyter Notebook for analyzing and exploring the dataset of a Superstore's orders. The dataset includes various attributes such as customer details, product information, and shipping data. The analysis focuses on understanding missing data, data structure, and basic summary statistics.

# Project Structure
Superstore_Orders.csv: The dataset containing the superstore's order data.
Superstore_Orders_Analysis.ipynb: A Jupyter notebook for performing data analysis on the Superstore orders dataset.

# Features
Data Loading and Exploration: The notebook loads the CSV file and performs initial exploration of the data, including viewing data types and null values.
Data Summary: It calculates the shape of the dataset, the number of rows, and columns, as well as the summary of each column.
Data Cleaning: The notebook identifies missing data using .isnull().sum().
Data Categorization: The dataset is divided into categorical and numerical columns for easier analysis.

# Analysis Steps
Dataset Inspection: We load and display the initial rows of the dataset using the head() function.
Data Information: The info() function is used to get an overview of the data types and non-null counts.
Missing Values Analysis: We check for missing data using isnull().sum() to determine which columns have null values.
Categorical and Numerical Data Segmentation: The dataset is divided into categorical and numerical columns to perform specific analyses.

# Outputs
The notebook outputs the number of missing values in each column of the dataset using .isnull().sum().
It also provides a summary of the dataset's structure, including the number of rows and columns.
