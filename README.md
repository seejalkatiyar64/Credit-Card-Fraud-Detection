This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. Given the highly imbalanced nature of fraud detection datasets, special attention is paid to preprocessing and evaluation metrics to ensure that the model performs well on rare fraud cases.
Challenges include:
Handling imbalanced datasets where fraud cases are a small fraction of total transactions.
Ensuring high precision to minimize false positives (flagging a valid transaction as fraud).
Ensuring high recall to detect as many fraud cases as possible.

Dataset
Source:/content/sample_data/creditcard.csv

Technologies Used
Language: Python 3.8+
platform: Google Colab
Libraries:
pandas, numpy (data handling)
matplotlib, seaborn (visualization)
scikit-learn, xgboost, imbalanced-learn (ML models & handling imbalance)

Modeling:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
Used GridSearchCV for hyperparameter tuning

Evaluation Metrics
Confusion Matrix
Precision, Recall, F1-Score

Achieved:
Accuracy: 0.9994
Precision: 1.0000
Recall: 0.7692
F1-Score: 0.8696


