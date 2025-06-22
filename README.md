# Final_ML_Project
Stroke Prediction using Machine Learning

Project Description
This project aims to predict the likelihood of a patient having a stroke based on various health-related features such as age, hypertension, heart disease, smoking status, and BMI. The dataset used comes from Kaggle and represents real-world healthcare data.
The goal is to build and evaluate classification models that can identify potential stroke cases, which is critical in medical decision-making and early intervention.

Machine Learning Algorithms Used
Logistic Regression – A statistical method for binary classification, used to model the probability of stroke occurrence.
Decision Tree Classifier – A flowchart-like tree structure that splits data into branches based on feature conditions.
Naive Bayes – A probabilistic model based on Bayes' Theorem with strong independence assumptions.

Final model choice was made based on evaluation using F1-score and confusion matrices, with Logistic Regression selected for its better performance on imbalanced data.

Libraries Used
Pandas – For data loading and preprocessing
NumPy – For numerical operations
Matplotlib & Seaborn – For visualization and plotting confusion matrices
Scikit-learn (sklearn) – For:
Model implementation (LogisticRegression, DecisionTreeClassifier, GaussianNB)
Data preprocessing (StandardScaler, train_test_split)
Evaluation metrics (accuracy_score, f1_score, confusion_matrix)

Dataset
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
