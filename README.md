# Phishing_Email_Detection_Model

## Overview

This project is a Machine Learning-based Phishing Email Detection System developed using Python and Scikit-learn. The model analyzes email content and classifies emails as either **Phishing** or **Safe** based on textual patterns and keywords.

## Features

* Detects phishing and legitimate emails
* Uses TF-IDF for text feature extraction
* Trains a Naive Bayes classification model
* Predicts whether an email is Phishing or Safe
* Displays model accuracy
* Generates a confusion matrix for evaluation

## Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Multinomial Naive Bayes

## Dataset

The dataset contains sample phishing and legitimate email messages used to train and test the model.

## Workflow

1. Create and prepare the email dataset.
2. Convert email text into numerical features using TF-IDF.
3. Split the dataset into training and testing sets.
4. Train the Naive Bayes classifier.
5. Evaluate model performance using accuracy and confusion matrix.
6. Predict whether a user-provided email is Phishing or Safe.

## Sample Prediction

Input:
Congratulations! Click here to claim your free reward.

Output:
Phishing

Input:
Please attend the team meeting scheduled for tomorrow.

Output:
Safe

## Learning Outcomes

* Understanding phishing attacks
* Text classification using machine learning
* Feature extraction with TF-IDF
* Model evaluation using accuracy and confusion matrix
* Practical application of cybersecurity concepts

## Disclaimer

This project is developed for educational and learning purposes only.

## Author

Manepalli Neha Gandhi
Cyber Security Internship Project
