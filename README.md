Telco Customer Churn Prediction
This project aims to analyze Telco customer data and build a logistic regression model to predict customer churn. The analysis includes data cleaning, visualization, correlation analysis, and model training and evaluation.

Table of Contents
Dataset Overview
Installation and Requirements
Code Structure
Usage
Results
License
Dataset Overview
The dataset used for this project, telco.csv, contains information about Telco customers, such as:

Customer Demographics (e.g., Gender, Age)
Account Information (e.g., Tenure, Contract Type, Payment Method)
Service Information (e.g., Monthly Charges, Total Charges)
Churn (whether the customer has churned or not)
Each row represents a unique customer.

Installation and Requirements
To run this code, you need:

Python 3.x
Required libraries, installable with:
bash
Copy code
pip install pandas seaborn matplotlib scikit-learn
Code Structure
The code is organized as follows:

Data Loading:

Load the telco.csv dataset.
Display the first five rows.
Data Cleaning:

Check for missing values.
Fill missing values in numeric columns with the median and categorical columns with the mode.
Data Exploration and Visualization:

Display summary statistics and data types.
Calculate the churn rate.
Visualize churn by contract type and monthly charges.
Correlation Analysis:

Plot a heatmap of the correlation matrix for numerical columns.
Data Preprocessing:

Encode categorical features (Gender, Churn, Contract, and PaymentMethod).
Define features and target variable (Churn).
Model Training:

Split the data into training and testing sets.
Train a logistic regression model to predict churn.
Model Evaluation:

Print a classification report.
Plot the confusion matrix for a visual assessment of the model's performance.
Usage
Prepare the Dataset:

Ensure telco.csv is available in the same directory as the code.
Run the Code:

Execute the code in a Python environment:
bash
Copy code
python churn_analysis.py
Interpret the Results:

The script will output:
Basic dataset information
Visualizations showing churn patterns
Model performance metrics
Results
Churn Rate: Displays the percentage of customers who churned.
Visualization: Shows the distribution of churn across contract types and monthly charges.
Model Performance: The logistic regression model’s accuracy and performance metrics are shown via the classification report and confusion matrix.
License
