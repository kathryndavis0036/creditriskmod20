# Credit Risk Module 20 Challenge
# Overview
This project uses a logistic regression model to predict loan risk based on historical data. The goal is to classify loans as either healthy (0) or high-risk (1).

# Data
- CSV File: lending_data.csv
- Features: Various features related to the loan
- Label: label (0 for healthy, 1 for high-risk)

# Steps
- Load Data: Read the CSV file into a Pandas DataFrame.
- Prepare Data:
  - Separate features (X) and labels (y).
  - Split the data into training and testing sets.
- Train Model:
  - Use logistic regression with random_state=1.
  - Fit the model on the training data.
- Evaluate Model:
  - Make predictions on the testing data.
  - Generate and review the confusion matrix.
  - 
# Results
The logistic regression model provides the following metrics:

- Accuracy: Overall correctness of the model.
- Precision: How many predicted high-risk loans are actually high-risk.
- Recall: How many actual high-risk loans are correctly identified.
- F1 Score: Balance between precision and recall.

# Usage
To run the code:

- Ensure all dependencies are installed (e.g., pandas, sklearn).
- Execute the Python script to perform the steps outlined.
