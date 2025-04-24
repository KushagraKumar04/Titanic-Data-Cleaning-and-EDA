# Titanic Data Cleaning and Exploratory Data Analysis

This repository contains a Jupyter Notebook that performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The analysis focuses on investigating inter-variable relationships to uncover patterns and trends within the data. This comprehensive analysis enhances understanding and lays the foundation for informed decision-making in subsequent analytical processes.

## Dataset

The dataset used in this analysis is the Titanic dataset, which is available on Kaggle. It contains information about the passengers who were on board the Titanic, including details such as age, gender, fare, cabin, and survival status.

## Notebook Overview

The notebook `Task2.ipynb` includes the following steps:

1. **Data Loading**: Loading the Titanic dataset into a Pandas DataFrame.
2. **Data Inspection**: Displaying the first few rows of the dataset, generating descriptive statistics, and checking for missing values and data types.
3. **Data Cleaning**:
   - Handling missing values by removing rows with missing 'Embarked' values and filling missing 'Cabin' and 'Age' values.
   - Checking for and handling duplicate entries.
4. **Data Visualization**:
   - Plotting the age distribution using a histogram.
   - Creating a count plot to visualize survival by gender.
   - Generating a scatter plot to explore the relationship between age and fare with survival status.

## Visualizations

The notebook generates the following visualizations to explore the data:

1. **Age Distribution**:
   ![Age Distribution](images/age_distribution.png)

2. **Survival by Gender**:
   ![Survival by Gender](images/survival_by_gender.png)

3. **Scatter Plot of Age vs Fare**:
   ![Age vs Fare](images/age_vs_fare.png)

## Installation and Usage

To run the notebook, you need to have Python installed along with the following libraries:

- pandas
- matplotlib
- seaborn

## Acknowledgements
The Titanic dataset is available on Kaggle: Titanic - Machine Learning from Disaster
