# Stroke Prediction using Machine Learning

## Project Overview
This project predicts the likelihood of a person having a stroke based on health-related factors such as age, hypertension, heart disease, BMI, and smoking status. The goal was to build and evaluate different machine learning models to identify which performs best on imbalanced medical data.

## What I Did
- Loaded and cleaned the stroke dataset from Kaggle  
- Handled missing values and encoded categorical features  
- Scaled numerical features for consistent model performance  
- Trained and tested three models:  
  - Logistic Regression  
  - Decision Tree  
  - Naive Bayes  
- Compared models using Accuracy and F1 Score  
- Used confusion matrices to evaluate predictions and balance between precision and recall  

## Model Selection
Because the dataset is imbalanced (few stroke cases), the **F1 Score** was more important than simple accuracy.  
- **Final Choice:** Logistic Regression — it achieved the best F1 Score and handled the imbalance more effectively.

## What I Learned
- How to clean and preprocess real-world datasets  
- How to train, evaluate, and compare multiple models  
- How to interpret model performance metrics like accuracy, precision, recall, and F1 Score  
- Gained experience with debugging, problem-solving, and exploring data science workflows  

## Tools and Libraries Used
- **Python**  
- **pandas**, **NumPy** – for data cleaning and preprocessing  
- **matplotlib**, **seaborn** – for visualization  
- **scikit-learn** – for building and evaluating models  

## Dataset
Source: [Stroke Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Author
**Zarema Kharachyk**  
-  [LinkedIn](https://www.linkedin.com/in/zarema-kharachyk/)  


Dataset:
Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
