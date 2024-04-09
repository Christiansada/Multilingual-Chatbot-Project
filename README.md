# Multilingual Chatbot Project

## Overview
This project aims to develop a multilingual chatbot capable of answering user queries in both Arabic and English languages. The chatbot uses natural language processing (NLP) techniques and deep learning models to understand and generate responses to user inputs.

## Features
- Language Detection: The chatbot is capable of detecting the language of the user input and selecting the appropriate model for generating responses.
- Arabic Model: The Arabic model preprocesses input text, performs language detection, and generates responses using a combination of TF-IDF vectorization, logistic regression, and sequence-to-sequence LSTM models.
- English Model: The English model follows a similar preprocessing and response generation approach, utilizing tokenization, LSTM models, and sequence-to-sequence architecture.
- Flask Web Interface: The chatbot is deployed using a Flask web application, allowing users to interact with it through a simple interface.
- Training and Deployment: The models are trained on separate datasets for Arabic and English questions and answers. The trained models are saved and deployed for inference using TensorFlow and Keras.

## Technologies Used
- Python
- TensorFlow
- Keras
- Flask
- NLTK
- scikit-learn

## Installation
To run the chatbot locally, follow these steps:
1. Install the required Python libraries using pip.
2. Clone the GitHub repository and navigate to the project directory.
3. Download the pre-trained models and datasets.
4. Run the Flask application to start the chatbot interface.

## Usage
1. Enter your query in the input field on the web interface.
2. Click the submit button to send the query to the chatbot.
3. The chatbot will process the input, detect the language, and generate a response.
4. View the response on the web interface.
