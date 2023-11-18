# Heart-Disease-Prediction-using-Machine-learning


## Implementation
I have uploaded a single.ipynb file containing the complete code with proper comments and subheadings. I used Google Colab for writing and implementing the code.
## Model Comparison

### Logistic Regression:
* Accuracy: 0.6831
* Precision (Class 1): 0.29
* Recall (Class 1): 0.68
* F1-Score (Class 1): 0.41
Logistic Regression achieves an accuracy of 0.6831. It has relatively low precision for class 1, which means it may generate many false positives. However, it has a relatively high recall for class 1, indicating it can capture a good portion of actual positive cases.

### Support Vector Machine (SVM):
* Accuracy: 0.7222
* Precision (Class 1): 0.27
* Recall (Class 1): 0.42
* F1-Score (Class 1): 0.33
SVM achieves an accuracy of 0.7222. It has similar precision and recall for class 1, indicating a more balanced performance, but the F1-score for class 1 is relatively low, suggesting there might be room for improvement.

### Decision Tree Classifier:
* Accuracy: 0.7058
* Precision (Class 1): 0.24
* Recall (Class 1): 0.39
* F1-Score (Class 1): 0.30
Decision Tree Classifier achieves an accuracy of 0.7058. It has low precision and recall for class 1, indicating that it may not perform well in capturing true positive cases.

### KNN Classifier:
* Accuracy: 0.6621
* Precision (Class 1): 0.25
* Recall (Class 1): 0.53
* F1-Score (Class 1): 0.34
KNN Classifier achieves an accuracy of 0.6621. It has relatively low precision for class 1 but higher recall, which suggests it is better at capturing true positive cases compared to Decision Tree.
Summary and Comparison:

## Summary
* SVM has the highest accuracy among the models, but its F1-score for class 1 is relatively low, indicating room for improvement in capturing true positive cases.
* Logistic Regression has a balanced recall and precision for class 1, indicating it can capture a good portion of actual positive cases.
* Decision Tree Classifier has the lowest F1-score for class 1, suggesting it may not be the best choice for this task.
* KNN Classifier has a higher recall but lower precision for class 1 compared to Logistic Regression, indicating that it captures more true positive cases but also generates more false positives.

So as per the conclusion, the best suitable model for this task is **"Logistic Regression Model"**.
