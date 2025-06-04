# Handwritten Digit Prediction

This project demonstrates a simple Machine Learning solution to classify handwritten digits (0–9) using the *MNIST digits dataset*. It uses Python libraries like NumPy, Pandas, Matplotlib, and Scikit-learn to train and evaluate a logistic regression model.

## 📌 Project Overview

- Classifies handwritten digits using image data
- Uses scikit-learn’s built-in load_digits() dataset (8x8 grayscale images)
- Applies *Logistic Regression* for digit classification
- Evaluates performance using accuracy score and confusion matrix
- Visualizes predictions on test samples

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset

- *Source*: sklearn.datasets.load_digits()
- *Images*: 8x8 grayscale (64 features)
- *Classes*: Digits from 0 to 9
- *Samples*: 1797

## Model Used

- *Logistic Regression* from sklearn.linear_model
- Achieved good prediction accuracy on unseen test data
