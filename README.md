Iris Species Classification: Model Comparison and Evaluation
This project demonstrates a complete machine learning workflow to classify Iris flowers into three species: Setosa, Versicolor, and Virginica. It compares three different algorithms and identifies the key features driving the predictions.

📋 Project Overview
The goal was to build a robust classifier using the classic Iris dataset. We performed exploratory data analysis, preprocessed the data, and trained multiple models to evaluate which one performs best on this specific classification task.

🛠️ Tech Stack
Language: Python
Libraries:
Data Handling: pandas, numpy
Machine Learning: scikit-learn
Visualization: matplotlib, seaborn
🚀 Workflow
Data Loading: Utilized the load_iris dataset from Scikit-Learn.
Preprocessing: Verified data quality (no missing values) and split the data into 80% training and 20% testing sets.
Model Training: Trained three distinct models:
Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest Classifier
Evaluation: Evaluated models using Accuracy, Precision, Recall, and F1-Score.
Feature Importance: Analyzed which physical traits of the flowers were most indicative of the species.
📊 Results & Insights
Model Comparison
All three models achieved exceptionally high performance on this dataset:

Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	1.0	1.0	1.0	1.0
KNN	1.0	1.0	1.0	1.0
Random Forest	1.0	1.0	1.0	1.0
Best Model: Random Forest
While all models performed perfectly, Random Forest was selected as the final model due to its ensemble nature, which typically offers better generalization on more complex datasets.

Feature Importance
The analysis revealed that petal characteristics are far more important than sepal characteristics for classification:

Petal Length (cm): ~44% importance
Petal Width (cm): ~42% importance
Sepal Measurements: <14% combined importance
🏁 Conclusion
The project successfully classified Iris species with 100% accuracy on the test set. The results confirm that petal dimensions are the primary distinguishing features for these species. This workflow provides a solid foundation for more complex multi-class classification problems.
