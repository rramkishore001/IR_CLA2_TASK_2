# Complaint Classification Using Machine Learning

## 1. Project Overview

This project focuses on classifying customer complaints into different product categories using Machine Learning and Natural Language Processing (NLP).

The system analyzes the complaint text and predicts the appropriate category. Three machine learning algorithms are implemented and compared to identify the best-performing model.

## 2. Dataset Description

**Dataset Name:** Complaint Processed

**Source:** Kaggle

**Dataset Used:** Balanced sample of 50,000 complaints

**Input Feature:** `narrative` – Customer complaint text

**Target Feature:** `product` – Complaint category

The dataset contains five categories:

1. Credit Reporting
2. Debt Collection
3. Mortgages and Loans
4. Credit Card
5. Retail Banking

Each category contains 10,000 records in the selected balanced sample.

## 3. Objectives

- Classify customer complaints into product categories.
- Apply NLP techniques for text preprocessing.
- Convert text into numerical features using TF-IDF.
- Implement and compare three machine learning algorithms.
- Identify the best-performing classification algorithm.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)

## 5. Data Preprocessing

The following preprocessing techniques are used:

- Convert text into lowercase.
- Remove unwanted characters and punctuation.
- Remove stop words.
- Clean and normalize complaint text.
- Convert text into numerical features using TF-IDF Vectorization.

## 6. Machine Learning Algorithms

Three algorithms are implemented:

### 1. K-Nearest Neighbors (KNN)
Classifies a complaint based on the most similar data points.

### 2. Decision Tree
Uses decision rules to classify complaints into different categories.

### 3. Support Vector Machine (SVM)
Finds an optimal decision boundary to distinguish between complaint categories.

## 7. Performance Evaluation

The algorithms are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Training Time
- Prediction Time

A comparison graph is generated to analyze the performance of all three algorithms.

## 8. Visualizations

The project includes:

- Class Distribution Graph
- Algorithm Performance Comparison Graph
- Training and Prediction Time Comparison Graph
- Confusion Matrix of the Best Algorithm

## 9. Project Workflow

1. Load the complaint dataset.
2. Explore the dataset and class distribution.
3. Preprocess complaint text.
4. Apply TF-IDF vectorization.
5. Train KNN, Decision Tree and SVM models.
6. Evaluate and compare model performance.
7. Identify the best algorithm using macro F1-score.
8. Generate and save graphs and the confusion matrix.

## 10. How to Run the Project

1. Download or clone this GitHub repository.
2. Open the notebook in Google Colab.
3. Upload `complaints_processed_sample_50k.zip`.
4. Extract the dataset.
5. Run all notebook cells in sequence.
6. View the comparison results and visualizations.

## 11. Expected Outcome

The project aims to develop an effective machine learning model for automatic customer complaint classification.

The best algorithm is selected based on the actual evaluation results, particularly the macro F1-score.

## 12. Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to automate customer complaint classification. Comparing KNN, Decision Tree and SVM helps identify a suitable algorithm for classifying customer complaints into different product categories.
