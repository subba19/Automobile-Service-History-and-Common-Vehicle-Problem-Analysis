# Automobile Service History and Common Vehicle Problem Analysis

## 1. Project Overview

This project focuses on analysing automobile service history and identifying common vehicle problems using Python and Machine Learning.

The main objective is to analyse vehicle maintenance records, identify frequently occurring problems, understand repair solutions and classify reported vehicle problems using a Machine Learning model.

## 2. Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Logistic Regression

## 3. Dataset Description

The dataset contains 508 records and 7 columns.

| Column Name | Description |
|---|---|
| CUSTOMER ID | Customer identification |
| CITY | Customer city |
| STATE | Customer state |
| SERVICE HISTORY | Previous service activities |
| COMMON PROBLEM | Reported vehicle problem |
| SOLUTION USED | Repair solution |
| VEHICAL COMPANY | Vehicle manufacturer |

## 4. Project Implementation

The project is implemented using the following steps:

1. Import Python libraries.
2. Upload and load the dataset.
3. Perform dataset inspection.
4. Check missing values and duplicates.
5. Clean and preprocess the data.
6. Perform Exploratory Data Analysis (EDA).
7. Analyse common vehicle problems.
8. Perform vehicle company-wise analysis.
9. Analyse service history.
10. Examine problem and solution relationships.
11. Apply Machine Learning using Logistic Regression.
12. Evaluate the model performance.

## 5. Machine Learning Algorithm

**Algorithm:** Logistic Regression

The model uses the following input features:

- City
- State
- Service History
- Vehicle Company

**Target Variable:** Common Problem

Customer ID and Solution Used are excluded from model training to avoid irrelevant identifiers and target leakage.

## 6. Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The actual performance scores are generated after executing the notebook.

## 7. Visualizations

The project generates the following visualizations:

- Common Vehicle Problems Graph
- Vehicle Company Analysis
- City-wise Service Records
- State-wise Service Records
- Service History Analysis
- Problem vs Solution Heatmap
- Machine Learning Confusion Matrix
- Model Performance Graph

## 8. How to Run the Project

1. Open Google Colab.
2. Create a new notebook.
3. Upload the project `.ipynb` file.
4. Run the Python cells sequentially.
5. Upload the automobile service dataset when prompted.
6. Execute the analysis and Machine Learning model.
7. View the generated graphs and evaluation results.

## 9. Expected Outcomes

- Identification of frequently reported vehicle problems.
- Analysis of vehicle service activities.
- Understanding of recorded repair solutions.
- Comparison of service records across vehicle companies.
- Classification of reported vehicle problems using Machine Learning.

## 10. Limitations

- The dataset does not contain vehicle sensor readings.
- Service dates and mileage information are unavailable.
- The dataset contains a limited number of records.
- The model classifies reported problems and does not predict future vehicle breakdowns.

## 11. Conclusion

This project demonstrates how Python, data analysis and Machine Learning can be used to analyse automobile service history. The analysis helps identify common vehicle problems, examine maintenance activities and understand recorded repair solutions.

## 12. Author

**Project:** Automobile Service History and Common Vehicle Problem Analysis

**Platform:** Google Colab

**Language:** Python
