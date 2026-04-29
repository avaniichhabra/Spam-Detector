# AI-Powered Spam Detector
A machine learning pipeline designed to classify SMS and email messages as Ham (Legitimate) or Spam. This project leverages Natural Language Processing (NLP) to analyze text patterns and provide real-time classification.

# Project Overview
The goal of this project is to build a robust classifier that filters out unwanted promotional content or phishing attempts. By utilizing a combination of text preprocessing and supervised learning, the model achieves high precision—ensuring that important messages are rarely misclassified as spam.

Key Features

1)Text Preprocessing: Automated cleaning including tokenization, stop-word removal, and stemming/lemmatization.

2)Vectorization: Implementation of TF-IDF (Term Frequency-Inverse Document Frequency) or Bag of Words to convert text into numerical features.

3)Multiple Models: Comparison between Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).

## Technical Architecture
The workflow follows a standard data science pipeline to ensure scalability and reproducibility:

Data Ingestion: Loading datasets (e.g., UCI SMS Spam Collection).

Exploratory Data Analysis (EDA): Visualizing word clouds and frequency distributions of spam vs. ham.

Feature Engineering: Extracting meaningful patterns from raw strings.

Model Training: Training the classifier on 80% of the data.

Evaluation: Using Confusion Matrices, F1-Score, and Precision-Recall curves.

## Performance Metrics
Accuracy - 98.3%
