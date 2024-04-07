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


### Model 5: Winning Model Performance Metrics:

- **Accuracy**: The model achieved an accuracy of approximately 82%, indicating that it correctly classified 82% of the instances in the test dataset.

- **Precision**: For predicting churn (class 1), the precision is 54%, implying that when the model predicts churn, it is correct 54% of the time. For non-churn (class 0), the precision is 91%.

- **Recall**: The recall for churn (class 1) is 68%, meaning that the model identified 68% of the actual churn cases correctly. For non-churn (class 0), the recall is 85%.

- **F1-score**: The F1-score, which is the harmonic mean of precision and recall, is 0.60 for churn (class 1) and 0.88 for non-churn (class 0).

### Actionable Insights and Business Recommendations

- **Precision and Recall Balance**: The model demonstrates a trade-off between precision and recall. While it achieves a high precision for non-churn customers, the precision for churn prediction is relatively lower. However, it manages to capture a significant portion of actual churn cases with a reasonable recall. This indicates that the model can effectively identify potential churners, albeit with some misclassifications.

- **Focus on Recall Improvement**: To improve the model's performance further, particularly in identifying churn cases, focus should be placed on improving recall without significantly sacrificing precision. This can be achieved through strategies such as feature engineering, exploring different model architectures, adjusting class weights, or collecting more diverse data.

- **Utilizing Predictions for Customer Retention**: Despite its limitations, the model can still provide valuable insights for the bank's customer retention strategies. By leveraging the model predictions, the bank can prioritize efforts towards retaining customers who are predicted to churn, offering tailored incentives, personalized communication, or targeted marketing campaigns to mitigate churn risk.

- **Continuous Model Monitoring and Improvement**: It's essential to continuously monitor the model's performance and retrain it periodically with updated data. As customer behavior evolves over time, the model needs to adapt to capture new patterns and trends accurately. Regular evaluation and refinement of the model will ensure its effectiveness in supporting the bank's customer retention efforts.

## Conclusion

While Model 5 provides a solid foundation for predicting customer churn, there's room for improvement to enhance its predictive power and applicability in real-world business scenarios. By focusing on refining the model and integrating its predictions into strategic decision-making processes, the bank can proactively address churn risk and foster long-term customer relationships.
