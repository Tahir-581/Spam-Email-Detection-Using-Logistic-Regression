# Spam-Email-Detection-Using-Logistic-Regression

This project demonstrates the implementation of a spam email detection system using a Logistic Regression model. It preprocesses email word count data, splits it into training and testing sets, trains a Logistic Regression classifier, and evaluates its performance. The project also includes an example of predicting whether a custom email is spam or not.



📄 Project Overview

Spam email detection is a binary classification task where emails are classified as either:

Spam (1): Unwanted or unsolicited messages.

Not Spam (0): Legitimate messages.


The dataset used contains word count features for emails and their corresponding labels (Spam or Not Spam). The model utilizes these features to identify patterns that distinguish spam from non-spam emails.




🛠️ Key Features

Data Preprocessing:

Mapped the Prediction column to a new label column (1 for Spam, 0 for Not Spam).

Removed unnecessary columns like Email No. and redundant features.


Logistic Regression Model:

Trained a logistic regression classifier to predict email categories.


Evaluation Metrics:

Used accuracy score and classification report to evaluate the model's performance.


Custom Predictions:

Allows prediction for a custom email using a word count vector.





📊 Dataset Information

The dataset is a CSV file with:

Email No.: Unique identifier for each email.

Word Count Features: Columns representing word occurrences in emails.

Prediction: Labels (1 = Spam, 0 = Not Spam).




🚀 How to Run the Project

Prerequisites

Ensure you have the following installed:

Python 3.x

Required libraries: pandas, scikit-learn




📝 Code Walkthrough

Step 1: Load the Dataset

The dataset is loaded into a pandas DataFrame and previewed to understand its structure.

Step 2: Data Preprocessing

The Prediction column is mapped to a label column (1 = Spam, 0 = Not Spam).

Irrelevant columns like Email No. and Prediction are dropped.

Features (X) and the target (y) are defined for training.


Step 3: Train-Test Split

The data is split into training and testing sets (80% training, 20% testing).

Step 4: Train Logistic Regression

A Logistic Regression model is trained on the training data.

Step 5: Predictions

Predictions are made on the test data.

Step 6: Model Evaluation

Model performance is evaluated using:

Accuracy Score: Measures the percentage of correct predictions.

Classification Report: Provides precision, recall, F1-score, and support for each class.


Step 7: Custom Email Prediction

A placeholder vector representing a new email is used to demonstrate how the model predicts whether an email is spam or not.
