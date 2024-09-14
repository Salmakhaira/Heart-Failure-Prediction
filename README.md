# Heart-Failure-Prediction

## Overview
This project involves the development of machine learning models to predict heart disease based on patient health data. The dataset used is the heart.csv, which includes various health indicators such as chest pain type, resting electrocardiogram results, and exercise-induced angina. Two models were implemented and evaluated: a Single Decision Tree Classifier and a Bagging Classifier.

## Dataset
The dataset consists of the following key features:
- Sex: Gender of the patient (1 = Male, 0 = Female).
- ChestPainType: Types of chest pain experienced.
- RestingECG: Results of resting electrocardiograms.
- ExerciseAngina: Whether the patient experiences angina induced by exercise (1 = Yes, 0 = No).
- ST_Slope: Slope of the peak exercise ST segment.
- HeartDisease: Target variable indicating the presence of heart disease (1 = Disease, 0 = No Disease).

## Project Workflow
1. Data Preprocessing :
- Encoding categorical variables into numerical format.
- Splitting the data into training and testing sets (80/20 split).

2. Modeling:
- Single Decision Tree Classifier: A simple decision tree was trained and tested.
- Bagging Classifier: A more advanced ensemble method using 100 decision trees was applied to improve accuracy and reduce variance.

3. Evaluation:
- Both models were evaluated using a classification report, including metrics such as precision, recall, F1-score, and accuracy.
- The Bagging Classifier outperformed the Single Decision Tree, achieving an accuracy of 84%, compared to 80% for the Single Decision Tree.
  
## Key Results
1. Single Decision Tree Classifier:
- Accuracy: 80%
- Precision, Recall, and F1-score metrics showed that the model had decent performance but with room for improvement.
  
2. Bagging Classifier:
- Accuracy: 84%
- Improved precision, recall, and F1-scores across both classes (1 and 0).
  
## Conclusion
The Bagging Classifier is the recommended model for heart disease prediction, offering higher accuracy and more balanced performance in comparison to the Single Decision Tree. This project demonstrates the importance of ensemble methods in improving the reliability of machine learning models.
