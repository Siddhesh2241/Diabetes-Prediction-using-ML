# Diabetes Prediction Using Classification Algorithms

![Test Image 1](https://res.cloudinary.com/grohealth/image/upload/c_fill,f_auto,fl_lossy,h_650,q_auto,w_1085/v1581695681/DCUK/Content/causes-of-diabetes.png)

This project aims to predict whether a patient has diabetes based on several medical attributes. The dataset used contains features such as glucose levels, blood pressure, insulin levels, and others to build predictive models using multiple classification algorithms. The algorithms used in this project are:

- Decision Tree
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

## Project Overview
This project involves building machine learning models to classify whether a patient is diabetic or not. The primary goal is to compare the performance of different algorithms and identify the most accurate model.

## Dataset
The dataset used for this project is from PIMA Indian Diabetes Dataset. It contains the following attributes:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
Blood Pressure: Diastolic blood pressure (mm Hg)
Skin Thickness: Triceps skinfold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: A function which scores likelihood of diabetes based on family history
Age: Age in years
Outcome: Class variable (0 or 1) where 1 denotes diabetes positive and 0 denotes diabetes negative
Algorithms Used
Decision Tree: A simple decision tree classifier that splits the data based on features and makes decisions by creating branches.

K-Nearest Neighbors (KNN): A non-parametric algorithm that classifies a data point based on how its neighbors are classified.

Logistic Regression: A statistical model that in its basic form uses a logistic function to model a binary dependent variable.

Support Vector Machine (SVM): A supervised machine learning algorithm that can classify cases by finding the best hyperplane that separates classes in the feature space.

Random Forest: An ensemble method that builds multiple decision trees and merges them together to get a more accurate and stable prediction.

## Model Evaluation
The models were evaluated using the following metrics:

## Accuracy: 
The proportion of correct predictions.
## Confusion Matrix: 
A matrix to visualize the performance of the classification model.
## Precision, Recall, F1-Score: 
These metrics help to understand the model’s ability to classify diabetic and non-diabetic patients.

## Results
Each algorithm was tested, and the performance metrics were compared. The Random Forest classifier performed best in terms of accuracy, followed by the Support Vector Machine and KNN.