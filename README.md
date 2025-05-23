# CustomerChurnPrediction
This project focuses on predicting customer churn for a telecom company. Due to class imbalance in the target variable, the Random Oversampling technique was applied to balance the dataset. Three tree-based classification models—Decision Tree, Random Forest, and XGBoost—were trained and evaluated. Random Forest emerged as the best-performing model and was further optimized using hyperparameter tuning, achieving a final accuracy of 0.81. Additionally, the top 10 most important features influencing churn were identified to provide valuable business insights.

# Data and Mehodology
The model was trained on a dataset of 2,000 customer records, including features like Tenure, Monthly Charges, Payment Method, Internet Service, and Churn, etc. Key steps included:
* Preprocessing: Handling missing values and encoding categorical variables.
* Model Selection: Random Forest was chosen.
* Training: Used an 80/20 train-test split with hyperparameter tuning via randomized search cv.

# Model Performance
The Random Forest model achieved:
 * Accuracy: 0.81
 * Precision: 0.80 
 * Recall: 0.83
 * F1-Score: 0.82
 * ROC-AUC: 0.90

 The high recall value indicates the model is effective at identifying customers who are likely to churn, which is crucial for proactive retention strategies.

