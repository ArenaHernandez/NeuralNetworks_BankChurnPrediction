# Neural Networks Bank Churn Prediction
 Predicting Customer Churn

## Summary

This project aims to develop a predictive model to identify potential customer churn in a banking context. The analysis utilizes neural network-based classification algorithms to predict whether a customer will leave the bank within the next six months.

## Model Performance

The best-performing model achieved an accuracy of approximately 82%. However, there's room for improvement in precision and recall, particularly for identifying churn cases. The precision for churn prediction is relatively lower, but the model captures a significant portion of actual churn cases with reasonable recall.

### Models Used:
- Model 1: Built with Adam optimizer
- Model 2: Built with Adam optimizer and Dropout
- Model 3: Built with balanced data using SMOTE and SGD optimizer
- Model 4: Built with balanced data using SMOTE and Adam optimizer
- Model 5: Built with balanced data using SMOTE, Adam optimizer, and Dropout

#### Model 5 (Best Model):
- Precision: 0.91
- Recall: 0.85
- F1-score: 0.88
- Accuracy: 0.82
- Support:
  - Class 0: 1327
  - Class 1: 340

## Business Recommendations

- **Balance Precision and Recall**: Focus on improving recall without sacrificing precision to better identify churn cases.
- **Utilize Predictions for Customer Retention**: Leverage model predictions to prioritize efforts towards retaining customers who are predicted to churn.
- **Continuous Model Monitoring and Improvement**: Regularly monitor the model's performance and update it with new data to ensure its effectiveness in supporting customer retention efforts.


