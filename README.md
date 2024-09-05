A Browser Extension to detect phishing emails and urls.

Email Phishing Detection using GRU Neural Network
This project is designed to detect phishing emails using a machine learning model based on a GRU (Gated Recurrent Unit) neural network. The system processes email content, extracts text features using TF-IDF, and classifies the email as either Phishing or Legitimate.

Key Features:
Preprocessing: Cleans the email text by removing special characters, stop words, and applying lemmatization and stemming.
Text Representation: Utilizes a pre-trained TF-IDF vectorizer to convert cleaned text into numerical features.
GRU Model: A GRU-based neural network is trained to classify emails based on the processed features.
Prediction: The model predicts whether an email is a phishing attempt or a legitimate message.
The pre-trained model and vectorizer are loaded, and predictions are made based on new email content. The project showcases an efficient approach to phishing detection using machine learning.
