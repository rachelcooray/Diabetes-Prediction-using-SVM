# Diabetes-Prediction-using-SVM
This project implements a Support Vector Machine (SVM) model to predict whether a patient has diabetes based on certain diagnostic measurements included in the dataset.
SVM is a supervised machine learning algorithm that can be used for classification and regression challenges. It works by finding the hyperplane that best divides a dataset into classes.

## Dataset

The dataset used for this project is the PIMA Indians Diabetes Database, which is available on Kaggle. The dataset includes several diagnostic measurements and an outcome column indicating whether or not the patient has diabetes.

Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
Target: Outcome (0 or 1, where 0 means non-diabetic and 1 means diabetic)

## Requirements

Python 3.x
NumPy
Pandas
Scikit-learn

## Usage

### Load and preprocess the dataset:
The dataset should be loaded into a pandas DataFrame and standardized using StandardScaler to ensure that all features have a mean of 0 and a standard deviation of 1.

### Train and test split:
The data is split into training and testing sets using an 80-20 ratio with stratification to ensure the same distribution of the outcome variable in both sets.

### Train the SVM model:
An SVM classifier with a linear kernel is trained on the training data.

### Evaluate the model:
The accuracy of the model is evaluated on both the training and testing sets.

### Make predictions:
Use the trained model to make predictions on new data points.

