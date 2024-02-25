# Direct-Marketing-System-Development

## Overview
This project involves developing a system for direct marketing, particularly focusing on whether clients will subscribe to a term deposit. The dataset provided by the Portuguese bank will be utilized for this purpose. As large amounts of data are expected, the system will be developed in a big data environment to ensure scalability.

## Preliminary Steps
1. Set up Jupyter Notebook in Microsoft Azure Cloud:
- Create a Jupyter Notebook environment in Microsoft Azure.
- Configure necessary compute instances.
2. Upload Dataset to Azure:
- Utilize Azure datastores to upload the dataset.
3. Data Understanding
- Explore dataset schema, first rows, descriptive statistics, and frequency tables.
- Provide insights into the distribution of variables using charts and visualizations.
4. Data Preparation
- Address missing values through imputation or deletion.
- Encode categorical variables for modeling compatibility.
- Apply transformations to variables based on distribution characteristics.
- Split the dataset into training and testing subsets for model evaluation.
- Assess and address class imbalance if present.
5. Modeling
- Model 1: Logistic Regression (Baseline Model): Implement logistic regression as a baseline model for initial evaluation.
- Model 2: Hyperparameter Tuning: Perform hyperparameter tuning via grid search: Run at least two different algorithms with at least 10 different hyperparameter-combinations. Identify the most promising model based on performance metrics.
6. Model Evaluation
- Evaluate all model fits using core parameters: Accuracy and Area Under Curve (AUC), ROC curves.
7. Final Model Selection
Report the final model that best fits the data based on AUC and overfitting control.
