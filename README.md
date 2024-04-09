# Multilingual Chatbot Project

## Overview
This project aims to develop a multilingual chatbot capable of answering user queries in both Arabic and English languages. The chatbot uses natural language processing (NLP) techniques and deep learning models to understand and generate responses to user inputs.

## Features
- Language Detection: The chatbot is capable of detecting the language of the user input and selecting the appropriate model for generating responses.
- Arabic Model: The Arabic model preprocesses input text, performs language detection, and generates responses using a combination of TF-IDF vectorization, logistic regression, and sequence-to-sequence LSTM models.
- English Model: The English model follows a similar preprocessing and response generation approach, utilizing tokenization, LSTM models, and sequence-to-sequence architecture.
- Flask Web Interface: The chatbot is deployed using a Flask web application, allowing users to interact with it through a simple interface.
- Training and Deployment: The models are trained on separate datasets for Arabic and English questions and answers. The trained models are saved and deployed for inference using TensorFlow and Keras.

## Project Components
The project comprises several components:
- **Data Collection**: We gathered datasets containing questions and answers in Arabic and English languages from various sources.
- **Language Detection**: We developed a language detection model to identify the language of the user input.
- **Preprocessing**: Data preprocessing involves cleaning and tokenizing text data for further processing.
- **Arabic Model**: The Arabic model consists of an encoder-decoder architecture implemented using LSTM (Long Short-Term Memory) networks.
- **English Model**: Similarly, the English model is based on an encoder-decoder architecture using LSTM networks.
- **Integration**: We integrated both models into a single system capable of handling queries in both languages.

## Workflow
1. **Data Preprocessing**: Cleaned and tokenized the text data, removed unnecessary characters, and normalized Arabic text.
2. **Model Training**: Trained separate models for Arabic and English languages using LSTM networks.
3. **Inference**: Developed inference models to generate responses based on user input.
4. **Integration**: Integrated the language detection model and both language-specific models into a unified chatbot system.

## Model Architecture
- **Encoder-Decoder Architecture**: Both Arabic and English models follow an encoder-decoder architecture for sequence-to-sequence learning.
- **LSTM Networks**: Long Short-Term Memory networks are used for capturing sequential dependencies in the input data.
- **Tokenizer**: Tokenization is performed using the Tokenizer class from the Keras library.

## Dataset
The chatbot models were trained on two separate datasets:

- Arabic Dataset: This dataset consists of Arabic questions and answers collected from various sources. It was preprocessed and used to train the Arabic model.

- English Dataset: Similarly, the English dataset contains questions and answers in English. It was preprocessed and used to train the English model.


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

## Future Improvements
- Enhance the chatbot's language understanding capabilities.
- Incorporate more languages into the multilingual chatbot.
- Fine-tune models for better performance.

## Acknowledgements
- The Arabert library for Arabic text processing.
- OpenAI for providing the base language model.
