# Heart Disease Prediction Model

This repository contains a machine learning project for predicting heart disease using the Heart Failure Prediction Dataset from Kaggle. The project aims to develop a model that can accurately classify patients as having heart disease or not, based on various health features. The models used in this project include Decision Tree, Random Forest, and XGBoost classifiers.

Dataset
The dataset used in this project is available on Kaggle: https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Ffedesoriano%2Fheart-failure-prediction

Dataset Features:

Age: Age of the patient (years)

Sex: Sex of the patient (M: Male, F: Female)

ChestPainType: Chest pain type (TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic)

RestingBP: Resting blood pressure (mm Hg)

Cholesterol: Serum cholesterol (mm/dl)

FastingBS: Fasting blood sugar (1: if FastingBS > 120 mg/dl, 0: otherwise)

RestingECG: Resting electrocardiogram results (Normal, ST: ST-T wave abnormality, LVH: Left ventricular hypertrophy)

MaxHR: Maximum heart rate achieved (Numeric value between 60 and 202)

ExerciseAngina: Exercise-induced angina (Y: Yes, N: No)

Oldpeak: Depression of ST (Numeric value measured in depression)

ST_Slope: Slope of the peak exercise ST segment (Up: upsloping, Flat: flat, Down: downsloping)

HeartDisease: Output class (1: heart disease, 0: Normal)

# Models Used

Decision Tree Classifier

Hyperparameters Tuned:
min_samples_split
max_depth
Performance evaluated on training and test sets.

Random Forest Classifier

Hyperparameters Tuned:
min_samples_split
max_depth
n_estimators
Performance evaluated on training and test sets.

XGBoost Classifier

Hyperparameters Tuned:
n_estimators
learning_rate
Utilizes early stopping to prevent overfitting.

# Results
Decision Tree:

Best min_samples_split and max_depth determined through cross-validation.

Model accuracy on training and test sets reported.

Random Forest:

Best min_samples_split, max_depth, and n_estimators determined through cross-validation.

Model accuracy on training and test sets reported.

XGBoost:

Early stopping used to prevent overfitting.

Best iteration identified.

Model accuracy on training and test sets reported.
