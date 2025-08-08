# Amazon Product Review Sentiment Analysis with RNN (LSTM)
This project focuses on analyzing Amazon product reviews and classifying them into positive or negative sentiments using Recurrent Neural Networks (RNN), specifically LSTM layers.
It includes data preprocessing with NLTK, sequence handling with TensorFlow/Keras, and model performance visualization.


## Project Overview
Goal: Predict the sentiment (positive/negative) of an Amazon product review.

Approach:

Load and clean text data.

Tokenize and remove stopwords.

Convert text to sequences and pad them for uniformity.

Train an RNN-based model (LSTM) for classification.

Evaluate and visualize results.

## Tech Stack
Programming Language: Python

Libraries Used:

pandas, numpy – Data handling and manipulation

matplotlib, seaborn – Data visualization

re – Regular expression text cleaning

nltk – Tokenization and stopword removal

tensorflow.keras – Model building (Embedding, LSTM, Dense layers)
