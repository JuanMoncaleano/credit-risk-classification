# credit-risk-classification

**Overview**

This project aims to build and evaluate machine learning models that can assess loan risk. The primary dataset used for this challenge comes from a peer-to-peer lending services company, and the goal is to determine the creditworthiness of borrowers.

**Structure**

credit_risk folder: Contains the main Jupyter Notebook (credit_risk_classification.ipynb) where all the machine learning models and analyses are performed.
Resources subfolder: Houses the dataset (lending_data.csv) used for analysis.
report.md: Provides a comprehensive write-up on the analysis carried out in the Jupyter Notebook.

**Models and Techniques**

Two main models were created:

Initial Logistic Regression: Serves as a baseline model for assessing loan risk.

Accuracy: 94.4%
Precision: 'Low risk': 1.00, 'High risk': 0.87
Recall: 'Low risk': 1.00, 'High risk': 0.89
Over-Sampled Logistic Regression: Addresses the issue of dataset imbalance through random over-sampling.

Accuracy: 99%
Precision: 'Low risk': 1.00, 'High risk': 0.99
Recall: 'Low risk': 0.99, 'High risk': 0.99

**Key Libraries**

numpy
pandas
pathlib
sklearn
imblearn

**Resources**

The article from Machine Learning Mastery was instrumental in understanding the concept of random over-sampling, a method not covered in our class but essential for this project. It offered a fresh perspective and approachable guidance based on what we had already learned.

**Summary and Recommendations**

After thorough analysis and evaluation, the Over-Sampled Logistic Regression model is recommended for implementation. It outperforms the initial Logistic Regression model in all evaluated metrics and is particularly effective at identifying 'High risk' borrowers, which is crucial for making sound financial decisions.

**How to Run the Code**

Clone this repository to your local machine.
Open credit_risk_classification.ipynb in Jupyter Notebook.
Run all the cells to perform the analysis and generate the machine learning models.
Read report.md for an in-depth understanding of the methodology and findings.
