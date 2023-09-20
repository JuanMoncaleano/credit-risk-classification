# Module 12 Report

**Overview of the Analysis**

For this analysis, my primary aim was to create a machine learning model that could effectively evaluate the risk level associated with new loan applications. The dataset I used comprised financial details from about 80,000 applicants. The data focused on variables like the loan amount, the applicant's income, debt level, and the number of accounts they hold. My task was to predict if an applicant is likely to default on their loan or not.

The first challenge I faced was the imbalance in the dataset. The majority of the data was skewed towards applicants who did not default on their loans. To overcome this, I went through various stages of the machine learning process, from data pre-processing to model selection, training, and evaluation.

For the base model, I used Logistic Regression. I also employed Random Over-Sampling as a resampling technique to address the imbalance in the dataset.

**Results**

My First Machine Learning Model: Initial Logistic Regression
Accuracy: The accuracy was 94.4%.
Precision: For 'Low risk' applicants, the score was 1.00, and for 'High risk,' it was 0.87.
Recall: The recall for 'Low risk' was 1.00, and for 'High risk,' it was 0.89.

My Second Machine Learning Model: Over-Sampled Logistic Regression

Accuracy: I achieved an accuracy rate of 99%.
Precision: The precision for 'Low risk' applicants remained at 1.00, but it improved to 0.99 for 'High risk' applicants.
Recall: The recall scores were also high—0.99 for both 'Low risk' and 'High risk.'

**Summary**

After evaluating both models, it's clear to me that the second model, which employed over-sampling, performed better in all metrics, be it accuracy, precision, or recall. This tells me that it's not only more accurate overall, but it's also more reliable in identifying both 'Low risk' and 'High risk' applicants.

The purpose of this model determines its effectiveness. In the loan assessment field, avoiding false negatives (labeling a 'High risk' applicant as 'Low risk') is usually more critical than minimizing false positives. My second model excels in precisely this aspect, offering high precision and recall for 'High risk' assessments.

Therefore, based on these considerations, I would recommend using my second machine learning model for evaluating loan applications. It shows superior predictive accuracy and is especially effective at identifying 'High risk' applicants, which is crucial for sound financial decision-making.
