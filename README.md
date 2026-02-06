# Loan-Approval-Prediction
👩‍💻 Loan Approval Prediction with Logistic Regression
📋 Overview

In this project, I built a binary classification model using logistic regression to predict whether a loan application would be approved based on applicants’ financial and credit-related information. The project followed a complete machine learning workflow, including data exploration, preprocessing, feature selection, model training, and evaluation using multiple classification metrics.

🎯 Learning Outcomes

By completing this lab, I was able to:

Preprocess financial data for machine learning applications

Implement logistic regression for binary classification problems

Evaluate classification model performance using multiple metrics

Visualize and interpret classification results

Apply machine learning techniques to solve financial industry problems

🔍 Project Description (with Confusion Matrix & ROC Curve)

After exploring and cleaning the dataset, I selected key financial features such as income, credit score, and loan amount, and applied feature scaling to ensure stable and effective model training. The dataset was then split into training and testing sets to evaluate real-world performance.

The logistic regression model was trained to predict loan approval as a binary outcome. Model performance was evaluated using multiple metrics, including accuracy, precision, recall, and ROC-AUC, providing a comprehensive view of classification quality.

To better understand prediction behavior, I used a confusion matrix visualization to break down model predictions into true positives, true negatives, false positives, and false negatives. This made it possible to clearly see how often the model correctly approved or rejected loans, as well as where it made errors. The confusion matrix highlighted the model’s tendency to correctly identify non-approved loans, while also revealing challenges in detecting approved loans, as reflected by the lower recall score.

In addition, I plotted the ROC Curve (Receiver Operating Characteristic Curve) to evaluate the model’s ability to distinguish between approved and non-approved loans across different classification thresholds. The ROC curve, along with the AUC score, demonstrated that the model has a reasonable ability to separate the two classes, even when the decision threshold is adjusted. This provides insight into how the model could be tuned depending on business priorities, such as reducing false approvals or minimizing missed approvals.

Overall, this project provided practical experience in evaluating classification models beyond accuracy alone and emphasized the importance of using confusion matrices and ROC curves to understand real-world trade-offs in financial decision-making systems.
