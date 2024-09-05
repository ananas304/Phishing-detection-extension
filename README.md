# Phishing Detection System
## A Browser Extension to detect phishing emails and urls ##
This repository contains a phishing detection system using machine learning models for both URLs and email content. The system is designed to identify potential phishing threats through the following components:

URL Analysis: Utilizes a Multilayer Perceptron (MLP) model to classify URLs as phishing or legitimate. Features extracted include URL length, hostname characteristics, and various heuristics to assess phishing risk.

Email Phishing Detection: Implements a Gated Recurrent Unit (GRU) model to analyze email content. This model processes text using TF-IDF vectorization, followed by preprocessing techniques such as tokenization, lemmatization, and stemming.

### Email Phishing Detection using GRU Neural Network
This project is designed to detect phishing emails using a machine learning model based on a GRU (Gated Recurrent Unit) neural network. The system processes email content, extracts text features using TF-IDF, and classifies the email as either Phishing or Legitimate.

#### Key Features:
1. Preprocessing: Cleans the email text by removing special characters, stop words, and applying lemmatization and stemming.
2. Text Representation: Utilizes a pre-trained TF-IDF vectorizer to convert cleaned text into numerical features.
3. GRU Model: A GRU-based neural network is trained to classify emails based on the processed features.
4. Prediction: The model predicts whether an email is a phishing attempt or a legitimate message.
The pre-trained model and vectorizer are loaded, and predictions are made based on new email content. The project showcases an efficient approach to phishing detection using machine learning.
