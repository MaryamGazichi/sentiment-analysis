
This project builds a sentiment analysis model using a pre-trained GloVe embedding and a custom IMDb movie review dataset.

## Features
- Preprocessing with Tokenizer and padding
- GloVe Embedding (100d)
- LSTM network with Dropout
- EarlyStopping for regularization
- Custom text prediction support

## Structure
- notebook/sentiment_glove_lstm.ipynb → model training
- test/predict_custom_sentence.ipynb → test on input sentence
- model/sentiment_model_glove.h5 → saved model
- data/IMDB-Dataset.csv → dataset

## How to Use
1. Mount Google Drive
2. Run training notebook
3. Save model
4. Run test notebook and enter a sentence

you can down load the dataset from: https://drive.google.com/file/d/1ae2O3XbwxHxbRWir84tu2dHupiPfOdS2/view?usp=sharing


download trained model : https://drive.google.com/file/d/1ryX7FW-tCKjujNfCARYgG0lj2rmj6OF2/view?usp=sharing

## Requirements
See `requirements.txt`