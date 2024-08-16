# Spma-Email-Detection

## Overview
This project aims to build a machine learning model to classify emails as spam or not spam. It utilizes a dataset of emails, preprocesses the data, extracts features, trains a logistic regression model, and evaluates its performance.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

## Installation
You can install the required libraries using pip:
```bash
pip install numpy pandas matplotlib scikit-learn
Dataset
The dataset used in this project is email_spam_data.csv, which should be placed in the D:/ directory. The dataset contains email messages and their labels (spam or ham).

## Steps

## Load and Preprocess Data:
Load the dataset and replace null values with blank spaces.
Remove unwanted columns and rename columns for clarity.
Encode categorical labels into numerical values.

## Feature Extraction:
Use TfidfVectorizer to convert email messages into feature vectors.

## Model Training:
Split the data into training and testing sets.
Train a Logistic Regression model on the training data.

## Model Evaluation:
Evaluate the model's accuracy on both training and test data.
Display accuracy using a bar chart.

## Prediction:
Use the trained model to predict whether a sample email is spam or not.

## Usage
To run the project, execute the Python script. The script will load the dataset, preprocess it, train the model, evaluate its performance, and predict the category of a sample email.

