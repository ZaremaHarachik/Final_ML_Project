# Final_ML_Project:
Stroke Prediction using Machine Learning

Project Description:
In this project, I built a machine learning model to predict if a person is likely to have a stroke based on health data. The dataset includes features like age, hypertension, heart disease, BMI, and smoking status.

What I Did:
Loaded and cleaned the stroke dataset from Kaggle
Handled missing values and encoded categorical features
Scaled numerical features
Trained and tested three models:
Logistic Regression
Decision Tree
Naive Bayes 

How I Chose the Best Model:
I looked at Accuracy and F1 Score
I also used confusion matrices to see how well each model predicted stroke cases
The dataset is imbalanced (very few stroke cases), so F1 Score was more important than accuracy
Final choice: Logistic Regression – It had the best F1 Score and handled the imbalanced data better

Tools and Libraries Used:
Python
Pandas and NumPy
Matplotlib and Seaborn (for plots)
Scikit-learn (for machine learning models and evaluation)

Dataset:
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
