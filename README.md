# English Tweets Sentiment Classifier (Deep Learning + Word Embeddings)

## Description
This project focuses on building a sentiment analysis classifier for English tweets using deep neural networks combined with pre-trained word embeddings (GloVe in Word2Vec format). The goal is to capture semantic relationships in text and explore more expressive feature representations beyond traditional vectorizers.

## Technical Approach
The model leverages GloVe Twitter embeddings to convert raw tweets into dense vector representations. A custom feedforward neural network architecture is trained on top of these embeddings, incorporating activation functions, dropout, batch normalization, and early stopping. Hyperparameters were optimized using Optuna.

## Features
- **Semantic embeddings**: Uses GloVe Twitter pre-trained vectors for input representation.
- **Deep learning model**: Customizable neural architecture with GELU activations and dropout.
- **Optimized training**: Incorporates early stopping and learning rate scheduling.
- **Hyperparameter tuning**: Search space defined and optimized using Optuna.

## Environment
This notebook was implemented and tested on **Kaggle**, utilizing its GPU-enabled environment and pre-installed packages.  
If running on other platforms like **Google Colab**, you may need to install additional libraries manually
