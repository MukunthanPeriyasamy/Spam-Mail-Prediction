# Spam Mail Prediction using Logistic Regression

Welcome to the Spam Mail Prediction project! This guide outlines the steps used to classify emails as spam or ham using logistic regression.

## Table of Contents

1. [Importing Libraries](#importing-libraries)
2. [Loading Dataset](#loading-dataset)
3. [Replacing Null Values](#replacing-null-values)
4. [Label Encoding](#label-encoding)
5. [Feature and Label Data](#feature-and-label-data)
6. [Splitting Data](#splitting-data)
7. [Transforming Text](#transforming-text)
8. [Training the Model](#training-the-model)
9. [Building a Predictive System](#building-a-predictive-system)

## 1. Importing Libraries

Start by importing the necessary libraries for data handling, model building, and evaluation.

## 2. Loading Dataset

Load your dataset, which should be in CSV format and include columns for the email text and labels.

## 3. Replacing Null Values

Ensure there are no null values in the email text by replacing them with an empty string.

## 4. Label Encoding

Convert the labels "Spam" to 0 and "Ham" to 1 for binary classification.

## 5. Feature and Label Data

Separate the dataset into features (email text) and labels.

## 6. Splitting Data

Divide the dataset into training and testing sets.

## 7. Transforming Text

Convert the email text data into numerical feature vectors using TF-IDF.

## 8. Training the Model

Train a logistic regression model using the training data.

## 9. Building a Predictive System

Make predictions on the test data and evaluate the model's performance using accuracy and other metrics.

## Running the Project

1. **Prepare your dataset** in a CSV file with columns `text` and `label`.
2. **Update file paths** in your code as needed.
3. **Run the script** to see the results and evaluate model performance.


Happy Coding! 🚀
