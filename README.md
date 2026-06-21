# Iris Flower Classification using Machine Learning

## Project Overview

This project builds and evaluates multiple Machine Learning models to classify Iris flower species using the famous Iris dataset. The objective is to compare different classification algorithms and identify the best-performing model based on evaluation metrics.

## Dataset

Source: Scikit-Learn Iris Dataset

Dataset Information:

* Total Samples: 150
* Features: 4

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* Target Classes:

  * Setosa
  * Versicolor
  * Virginica

## Problem Statement

Predict the species of an Iris flower based on its physical measurements and compare multiple Machine Learning algorithms to determine the most accurate classifier.

## Project Workflow

### 1. Data Loading and Exploration

* Loaded the Iris dataset
* Created a Pandas DataFrame
* Explored dataset statistics
* Checked class distribution
* Verified missing values

### 2. Data Preprocessing

* Checked for missing values
* Verified data quality
* Split dataset into training and testing sets (80:20)

### 3. Feature Engineering

* Performed feature importance analysis
* Identified the most influential features
* Analyzed relationships among variables

### 4. Model Training

The following Machine Learning algorithms were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

### 5. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

A comparison table was created to compare model performance.

### 6. Best Model Analysis

The best-performing model was selected based on evaluation metrics.

Additional analysis included:

* Confusion Matrix
* Feature Importance Visualization
* Performance Interpretation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Results

The machine learning models achieved excellent classification performance on the Iris dataset.

Key observations:

* Random Forest achieved the highest overall performance.
* Petal Length and Petal Width were the most important features.
* The dataset is highly separable, resulting in very high accuracy across all models.

## Conclusion

1. Three classification models were successfully trained and evaluated.
2. Random Forest delivered the best overall performance.
3. Petal Length and Petal Width were the most influential features.
4. The Iris dataset is highly suitable for classification tasks.
5. Random Forest was selected as the final model due to its accuracy and robustness.

## Project Structure

├── Iris_Classification_ML_Project.ipynb
├── Dataset
├── Model Evaluation Results
├── Confusion Matrix
└── README.md

## Author

Mohan Teja Parim

## Internship

Pluto Academy AI & ML Internship Program
