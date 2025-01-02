# Heart Disease Prediction

The **Heart Disease Prediction** project aims to predict whether a person has heart disease based on a range of health features using a **Logistic Regression** model. By analyzing factors like age, cholesterol levels, maximum heart rate, and other medical parameters, this model classifies individuals as either having a **Healthy Heart** (0) or a **Defective Heart** (1).

---

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Data](#data)
- [Model Training & Evaluation](#model-training-evaluation)
- [Making Predictions](#making-predictions)
- [License](#license)

---

## Project Overview

Heart disease is a leading cause of death worldwide, and early detection can be crucial for saving lives. This project uses a **Logistic Regression** model to predict heart disease presence based on patient data.

The dataset used in this project contains 303 samples with 14 features, including details about a person's age, sex, cholesterol levels, resting blood pressure, and maximum heart rate. The model predicts whether a person is at risk of heart disease based on these factors.

### Key Steps in the Project:
1. **Data Collection**: The dataset is obtained from the UCI Machine Learning Repository.
2. **Data Preprocessing**: The data is split into training and testing sets, ensuring a balanced representation of heart disease presence.
3. **Model Training**: The logistic regression model is trained on the training set.
4. **Model Evaluation**: The model's performance is evaluated using accuracy scores on both training and test data.
5. **Prediction**: The trained model is used to predict the likelihood of heart disease for new input data.

---

## Key Features

- **Logistic Regression Model**: Utilizes logistic regression, a simple yet powerful model for binary classification.
- **Data Preprocessing**: Handles missing data, splits the dataset, and standardizes the features.
- **Accuracy Evaluation**: Provides performance metrics such as accuracy on both training and testing datasets.
- **Prediction System**: Allows users to input their health data to predict the presence of heart disease.

---

## Installation

Follow these steps to set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/iDharitri-Raj/Heart_Disease_Prediction
   ```
2. Install required libraries (if not already installed):
   ```bash
   pip install numpy pandas scikit-learn
   ```

---

## Data
The dataset used in this project contains 303 samples and 14 columns. Below are the key features:

- age: Age of the person.
- sex: Gender of the person (1 = Male, 0 = Female).
- cp: Chest pain type (categorical).
- trestbps: Resting blood pressure.
- chol: Serum cholesterol.
- fbs: Fasting blood sugar.
- restecg: Resting electrocardiographic results.
- thalach: Maximum heart rate achieved.
- exang: Exercise induced angina.
- oldpeak: Depression induced by exercise relative to rest.
- slope: Slope of the peak exercise ST segment.
- ca: Number of major vessels colored by fluoroscopy.
- thal: Thalassemia.
- target: Heart disease presence (1 = Yes, 0 = No).

---

## Model Training & Evaluation

### Model Used:
- Logistic Regression

### Performance Metrics:
- Training Accuracy: 85.12%
- Test Accuracy: 81.97%

---

## Making Predictions
Once the model is trained, it can be used to predict whether a person has heart disease based on input data. For example, by inputting health-related features like age, cholesterol level, and exercise capacity, the model will return:

- 0: Healthy Heart
- 1: Defective Heart

This predictive capability can be valuable for early detection and prevention of heart disease.

---

### License
This project is licensed under the [**MIT License**](LICENSE) 

