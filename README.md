TASK 4 Classification with Logistic Regression


Dataset: Used the Breast Cancer Prediction dataset from Kaggle to classify tumors as Malignant (1) or Benign (0).

Preprocessing: Removed unnecessary columns, converted diagnosis labels to binary, split data into train/test sets, and standardized features.

Model: Trained a Logistic Regression model on the standardized training data.

Evaluation: Assessed the model using confusion matrix, precision, recall, accuracy, and ROC-AUC score.

Threshold Tuning: Adjusted the classification threshold (e.g., 0.3 instead of 0.5) to balance between precision and recall depending on the use case.

Sigmoid Function: Logistic regression uses the sigmoid function to output probabilities between 0 and 1, which helps decide the final class label based on the chosen threshold.
