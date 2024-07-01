# CodeAlpha__Tasks


Task 1: Titanic Classification
Objective: Create a classification system to predict whether a person would survive the Titanic sinking based on socio-economic status, age, gender, and other factors.

Steps:

Load and Explore the Dataset:

Import necessary libraries.
Load the Titanic dataset.
Inspect the first few rows of the dataset.
Preprocess the Data:

Handle missing values:
Fill missing Age values with the median.
Drop the Cabin column due to a high number of missing values.
Fill missing Embarked values with the mode.
Encode categorical variables (Sex and Embarked).
Select relevant features for the model (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked).
Split the Data:

Split the dataset into training and testing sets.
Train a Machine Learning Model:

Use a Random Forest classifier.
Train the model on the training data.
Evaluate the Model:

Make predictions on the test data.
Evaluate the model's performance using metrics like accuracy, classification report, and confusion matrix.
