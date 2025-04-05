Car Crash Data Classification

This project involves analyzing a car crash dataset to predict various injury types resulting from car accidents. The goal of the project is to build a machine learning model to predict whether an accident results in fatal or incapacitating injuries based on features such as time, location, and collision type.

Dataset

The dataset used for this project contains car crash data with several attributes, including:

Year: Year of the accident
Month: Month of the accident
Day: Day of the accident
Weekend?: Whether the accident occurred on a weekend
Hour: Hour of the day when the accident occurred
Collision Type: Type of collision (e.g., 1-Car, 2-Car, etc.)
Injury Type: Injury type resulting from the accident (e.g., Fatal, Incapacitating, Non-incapacitating)
Primary Factor: The primary factor responsible for the accident
Reported Location: The location of the accident
Latitude: Latitude of the accident
Longitude: Longitude of the accident
Objective

The primary objective of this project is to predict the injury type of a car crash accident (whether it is Fatal, Incapacitating, or Non-incapacitating).

The specific goals are:
Preprocessing the Data: Handle missing values, encode categorical variables, and scale numerical features.
Model Development: Use machine learning classification algorithms such as Logistic Regression to predict injury types.
Evaluation: Assess the performance of the model using various evaluation metrics such as accuracy, precision, recall, and F1-score.
Steps Taken

1. Data Preprocessing
Missing Data Handling: Removed or imputed missing data in the dataset.
Encoding Categorical Variables: Applied one-hot encoding to categorical columns like Weekend?, Collision Type, and Injury Type.
Feature Scaling: Scaled the numerical features (such as Latitude, Longitude, and Hour) using Min-Max scaling to ensure consistency.
2. Model Building
Model Selection: Logistic Regression was chosen as the primary model for classification.
Multi-output Classification: The task was framed as a multi-output classification problem, predicting multiple injury categories (e.g., Fatal, Incapacitating, etc.).
3. Model Evaluation
Train/Test Split: The data was split into 80% training and 20% test sets.
Performance Metrics: Model performance was evaluated using accuracy, precision, recall, F1-score, and confusion matrices.

