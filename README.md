# Next-Word-Prediction-Using-LSTM


#Overview
This project implements a next word predictor using Long Short-Term Memory (LSTM) networks. The model is trained on a text corpus and can predict the next word in a sequence of words.

#Features
Data Preprocessing: Tokenizes and cleans text data.
Sequence Creation: Generates sequences of words for model training.
LSTM Model: Uses an LSTM-based neural network for next word prediction.
Prediction Functionality: Predicts the next word given a seed text.

#Data Preparation
The text data is tokenized and cleaned to remove unwanted characters and punctuation.
Sequences of words are created using a sliding window approach and padded to ensure uniform length.

#Model Architecture
The model consists of an embedding layer, an LSTM layer, and a dense output layer with a softmax activation functio
