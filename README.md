# Diabetes Prediction Using Classification Algorithms

![Test Image 1](https://res.cloudinary.com/grohealth/image/upload/c_fill,f_auto,fl_lossy,h_650,q_auto,w_1085/v1581695681/DCUK/Content/causes-of-diabetes.png)

This project aims to predict whether a patient has diabetes based on several medical attributes. The dataset used contains features such as glucose levels, blood pressure, insulin levels, and others to build predictive models using multiple classification algorithms. The algorithms used in this project are:

- Decision Tree
- K-Nearest Neighbors 
- Logistic Regression
- Support Vector Machine 
- Random Forest
- Bagging Classifier
- Boosting Classifier
- Voting Classifier

## Project Overview
This project involves building machine learning models to classify whether a patient is diabetic or not. The primary goal is to compare the performance of different algorithms and identify the most accurate model.

## Dataset
The dataset used for this project is from PIMA Indian Diabetes Dataset. It contains the following attributes:

- **Pregnancies** : Number of times pregnant
- **Glucose** : Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- **Blood Pressure** : Diastolic blood pressure (mm Hg)
- **Skin Thickness** : Triceps skinfold thickness (mm)
- **Insulin** : 2-Hour serum insulin (mu U/ml)
- **BMI** : Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction** : A function which scores likelihood of diabetes based on family history
- Age: Age in years
- Outcome: Class variable (0 or 1) where 1 denotes diabetes positive and 0 denotes diabetes negative
  Algorithms Used

## Model Evaluation
The models were evaluated using the following metrics:

## Accuracy: 
This section provides an analysis of the various models based on their training and testing accuracies.

| Algorithm               | Training Accuracy | Testing Accuracy |
|-------------------------|-------------------|------------------|
| Decision Tree           | 1.0               | 0.70             |
| K-Nearest Neighbors     | 0.87              | 0.73             |
| Logistic Regression     | 0.74              | 0.77             |
| SVM                     | 0.77              | 0.74             |
| Random Forest           | 1.0               | 0.74             |
| Bagging Classifier      | 1.0               | 0.75             |
| Boosting Classifier     | 1.0               | 0.70             |
| Voting Classifier       | 1.0               | 0.73             |

## Overall Conclusion

- **Overfitting**: Several models (Decision Tree, Random Forest, Bagging Classifier, Boosting Classifier, and Voting Classifier) show signs of overfitting with perfect training accuracies but lower testing accuracies.
 
- **Best Generalization**: Logistic Regression and SVM show a good balance between training and testing performance, indicating better generalization.

- **K-Nearest Neighbors** also performs relatively well with moderate training and testing accuracy, suggesting it could be a reliable model for this dataset.

If the goal is to select a model that generalizes well to new data, Logistic Regression and SVM are strong candidates based on the provided accuracies.

