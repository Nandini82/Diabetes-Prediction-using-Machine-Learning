# Diabetes Prediction using Machine Learning Algorithms
This project predicts whether a patient has diabetes or not based on various health-related features. The following machine learning algorithms were used:

1) Naive Bayes
2) Support Vector Machine (SVM)
3) Logistic Regression
4) Random Forest Classifier
5) Bagging Classifier

## Dataset
The dataset used in this project is the Pima Indians Diabetes Database, which is publicly available on the UCI Machine Learning Repository. The dataset contains 768 rows and 9 columns, where each row represents a patient and each column represents a feature. The target variable is whether the patient has diabetes or not.

## Data Preprocessing
Here, we have deal with the null values and replaced them with median of a particular column that comprises of the null data.

## Result
The following table shows the accuracy of each machine learning algorithm used in the project:

| Algorithm              | Accuracy      | 
| ---------------------- | ------------- | 
|Naive Bayes	           | 0.775         | 
|Support Vector Machine  | 0.792         | 
|Logistic Regression     | 0.779         |
|Random Forest Classifier| 0.779         |
|Bagging Classifier      | 0.800         |

Based on the results, the Bagging Classifier algorithm performs the best with an accuracy of 0.80.
