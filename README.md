# Prodigy_DS_02

## Titanic Dataset Analysis

### Project Overview
This project involves data cleaning, preprocessing, and exploratory analysis of the Titanic dataset. Key insights include survival rates by gender, age distribution, and the influence of passenger class on survival.

### Steps in Analysis
1. Data Cleaning & Preprocessing
- Handled missing values by filling 'Age' with the median, filling 'Embarked' with mode, and dropping the 'Cabin' column.
- Converted 'Sex' to a binary format and created dummy variables for 'Embarked' categories.
- Dropped irrelevant columns: 'PassengerId', 'Ticket', and 'Name' for more focused analysis.

2. Exploratory Data Analysis (EDA)
- Created visualizations to understand survival rates by gender, age distribution, and survival based on passenger class.
- Generated a heatmap to display feature correlations.
Visualizations
- Correlation Heatmap: Shows relationships between features.
- Survival Rate by Gender: Analyzes the effect of gender on survival rates.
- Age Distribution: Visualizes the age distribution of passengers.
- Survival by Passenger Class: Examines how class affected survival chances.

3. Requirements
Python Libraries: Pandas, Seaborn, Matplotlib

4. Dataset
The dataset used is the Titanic - Machine Learning from Disaster dataset from Kaggle. It contains information about Titanic passengers, including demographic details, ticket information, and survival status.

Features: Age, Sex, Passenger Class, Embarked Location, etc.
Target: Survival (0 = No, 1 = Yes)

5. Usage
Clone the repository and run the provided code to reproduce the analysis and visualizations.
