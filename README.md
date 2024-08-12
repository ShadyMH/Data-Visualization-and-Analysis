# Data-Visualization-and-Analysis
Here's an updated README draft that includes the details from the provided Python script and additional project files:

---

# Graduation Project: Urban Waste Analysis in Israeli Cities

## Project Overview

This project focuses on analyzing urban waste data across different cities in Israel. The primary goal is to understand the factors influencing public waste disposal behaviors and develop predictive models to forecast these patterns. The analysis involves a wide range of demographic, infrastructural, and environmental data, sourced from governmental databases. Additionally, an interactive Tableau dashboard is included, allowing users to explore waste data by hovering over or clicking on cities.

## Files in the Repository

### 1. Excel Files
The project utilizes several Excel files containing cleaned and processed data for analysis:

- **`model_df_noNanRows.xlsx`**: Dataset with all rows where there were no missing values.
- **`model_df_noNanRows_afterDrop.xlsx`**: Similar to the above, but with additional columns removed for more focused analysis.
- **`data_clean.xlsx`**: The cleaned dataset, ready for analysis.
- **`df_only_neg.xlsx`**: A filtered dataset containing only negative cases or instances.
- **`model_df.xlsx`**: The primary dataset used for modeling.
- **`model_df_noNanColumns.xlsx`**: Dataset with columns containing no missing values.
- **`model_df_noNanColumns_afterDrop.xlsx`**: Similar to the above but with further column reductions.
- **`model_df_noNanColumns_Classes.xlsx`**: The dataset categorized into different classes for further analysis.

### 2. Python Script

- **`project.py`**: This Python script handles the data processing, cleaning, merging, and model training steps. It includes:
  - Importing datasets from Google Drive.
  - Data cleaning and transformation.
  - Feature engineering, such as converting categorical variables into dummy variables and scaling numerical features.
  - Merging datasets to create a comprehensive data frame for analysis.
  - Implementation of various predictive models, including Linear Regression, Random Forest, and XGBoost for both regression and classification tasks.
  - Statistical tests, including Chi-Square tests for gender, age groups, days of the week, and different areas.
  - Visualization of feature importance and correlation between variables.

### 3. Tableau Workbook

- **`Project Final.twbx`**: This Tableau workbook includes multiple spreadsheets with different data sources and an interactive dashboard that allows users to explore the waste data by hovering over or clicking on cities. The dashboard provides a visual representation of the data, making it easy to identify trends and gain insights.

### 4. Documentation and Project Report

- **`פרויקטגמר.docx`**: The final project report, which includes detailed sections on background, literature review, methodologies, statistical methods, predictive models, results, and conclusions. It provides a comprehensive overview of the research conducted and the findings derived from the analysis.
- **`תקציר.docx`**: A summary document that gives an overview of the project, including its objectives, methods, and key findings.

## Project Summary

### Background
The project investigates waste disposal patterns in Israeli cities by analyzing a variety of demographic, infrastructural, and environmental data. The research aims to identify key factors that influence public waste disposal behaviors and develop predictive models to help in efficient waste management.

### Methodologies
- **Statistical Methods:** Various statistical techniques were employed to understand the relationships between different variables.
- **Predictive Models:** Linear Regression, Random Forest Regression, and XGBoost Regression models were implemented to predict waste disposal patterns. Additionally, a Gradient Boosting Classifier was used to categorize waste disposal behaviors into different levels (Low, Medium, High).

### Results
The analysis revealed significant differences in waste disposal behaviors across different population groups and cities. Infrastructural and environmental factors were also found to have a substantial impact on the amount of waste disposed of in public spaces.

### Challenges and Improvements
The project faced challenges such as overfitting in the predictive models and difficulty in accurately predicting behaviors due to the complexity of human behaviors in urban environments. Various steps were taken to address these issues, including feature selection, outlier treatment, and data splitting strategies.

## Interactive Dashboard

The Tableau dashboard included in this project allows users to explore the data visually by interacting with the map and charts. Users can hover over or click on cities to view detailed information on waste disposal behaviors and related factors.

## How to Use

1. **Data Exploration:**
   - Open the Excel files using any spreadsheet software like Microsoft Excel, Google Sheets, or LibreOffice Calc.
   - Each file contains data at different stages of preparation, from raw to processed and ready for modeling.

2. **Interactive Dashboard:**
   - Open the Tableau workbook (`.twbx` file) using Tableau Public or Tableau Desktop.
   - Navigate to the dashboard to interactively explore the data.

3. **Python Script:**
   - The Python script (`project.py`) can be run in a Python environment to replicate the data processing and model training steps.
   - Ensure all dependencies are installed before running the script.


