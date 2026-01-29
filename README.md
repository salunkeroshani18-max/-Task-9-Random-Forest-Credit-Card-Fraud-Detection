# Credit Card Fraud Detection using Random Forest

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. Since fraud detection datasets are highly imbalanced, accuracy is not a reliable metric. Therefore, precision, recall, and F1-score are used for proper evaluation.

A Random Forest classifier is implemented and compared with a baseline Logistic Regression model to analyze performance.

---

## Dataset
- Source: Kaggle Credit Card Fraud Detection Dataset
- Target Column: Class
  - 0 → Non-Fraud
  - 1 → Fraud
- The dataset is highly imbalanced with very few fraud cases.

Note: The dataset is not included in this repository due to size limitations. Please download it from Kaggle and place it in the project folder.

---

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Project Workflow
1. Loaded and explored the dataset
2. Analyzed class imbalance
3. Separated features and target variable
4. Performed stratified train-test split
5. Trained Logistic Regression as a baseline model
6. Trained Random Forest classifier
7. Evaluated models using precision, recall, and F1-score
8. Analyzed feature importance

---

## Models Used
- Logistic Regression (Baseline Model)
- Random Forest Classifier (Main Model)

---

## Evaluation Metrics
Due to class imbalance, the following metrics were used:
- Precision
- Recall
- F1-Score
- Confusion Matrix

Recall for fraud detection was prioritized to minimize false negative cases.

---

## Results
- Random Forest performed better than Logistic Regression
- Improved recall and F1-score for fraud detection
- Effective handling of imbalanced data

---

## Feature Importance
Random Forest provides feature importance scores that help identify key indicators of fraudulent transactions.

---

## Conclusion
The Random Forest model successfully detected fraudulent credit card transactions and handled class imbalance effectively. Using appropriate evaluation metrics ensured reliable performance assessment.

---

## Future Scope
- Apply SMOTE for better class balancing
- Use advanced algorithms like XGBoost and LightGBM
- Perform hyperparameter tuning
- Deploy the model as a web application

---

## Author
AI & ML Intern
