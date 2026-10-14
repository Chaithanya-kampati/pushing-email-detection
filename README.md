# Phishing Email Detection Model

## Objective

The objective of this project is to detect whether an email is Safe or Phishing using Machine Learning.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset

The dataset contains email messages classified into two categories:

- Safe
- Phishing

## Machine Learning Process

1. Load the email dataset.
2. Convert email labels into numerical values.
3. Split the dataset into training and testing data.
4. Convert email text into numerical features using TF-IDF.
5. Train a Logistic Regression model.
6. Predict whether emails are Safe or Phishing.
7. Calculate model accuracy.
8. Generate a confusion matrix.

## Model Used

Logistic Regression is used as the Machine Learning classification model.

## Output

The program displays:

- Accuracy
- Classification Report
- Confusion Matrix
- Predictions for new emails

## How to Run

Open the terminal in the project folder and run:

python phishing_detection.py

## Result

The model predicts whether a given email is:

Safe

or

Phishing