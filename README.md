# 📧 Email Spam Prediction Using Machine Learning

## Project Overview

Email Spam Prediction is a machine learning application that classifies email messages as Spam or Not Spam (Ham).

The application uses Natural Language Processing (NLP), TF-IDF text vectorization, and a trained machine learning classifier to predict whether an email is spam.

A simple web interface is developed using Streamlit so users can enter email messages and receive predictions.

## Objectives

- Detect spam emails automatically.
- Classify emails as Spam or Ham.
- Apply Natural Language Processing techniques.
- Build an interactive web application using Streamlit.
- Demonstrate the practical use of machine learning.

## Technologies Used

- Python
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes (if used by the trained model)
- Joblib
- Streamlit
- Google Colab
- GitHub

## Features

- Simple user interface.
- Email text input.
- Automatic text processing.
- Machine learning-based classification.
- Instant prediction results.

## How It Works

1. The user enters an email message.
2. TF-IDF converts the text into numerical features.
3. The trained model processes the features.
4. The model predicts whether the message is Spam or Ham.
5. The result is displayed on the screen.

## Project Structure

```text
email-spam-prediction/
├── app.py
├── spam_vectorizer.pkl
├── spam_classifier.pkl
├── requirements.txt
└── README.md
