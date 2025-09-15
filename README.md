# Predicting-Customer-Churn-Using-ANN
Predicting Customer Churn Using Artificial Neural Network


##### Customer Churn Prediction

This project builds a machine learning model to predict customer churn using structured banking data. Key highlights:

Data preprocessing: Handling missing values, encoding categorical variables, feature scaling, and balancing classes using SMOTE.

Modeling: Developed a deep neural network with multiple dense layers and dropout for regularization.

Evaluation: Achieved an ROC-AUC score of ~0.85, with a test accuracy of approximately 83%.

Performance insights:

True Negatives: 1344 (correctly predicted non-churners)

False Positives: 249 (non-churners incorrectly predicted as churners)

False Negatives: 125 (missed churners)

True Positives: 282 (correctly predicted churners)

Next steps: Potential improvements include threshold tuning, class weighting, and experimenting with tree-based models like XGBoost for better churn detection.

This project demonstrates practical techniques in imbalanced classification, neural network design, and performance evaluation for customer retention.
