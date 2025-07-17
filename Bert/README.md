# Sentiment Analysis with DistilBERT

This project performs sentiment analysis on IMDb movie reviews using the DistilBERT transformer model from Hugging Face.

## 📚 Dataset
The dataset contains 50,000 labeled reviews from IMDb. Each review is labeled as either `positive` or `negative`.

We used a sample of 6000 reviews to reduce training time, and split the data into 80% training and 20% test sets.

## 🧠 Model
- Model: `TFDistilBertForSequenceClassification`
- Tokenizer: `DistilBertTokenizerFast`
- Architecture: Pretrained DistilBERT with a classification head
- Loss: SparseCategoricalCrossentropy (from_logits=True)
- Optimizer: Adam
- Epochs: 3 (with early stopping)
- Batch size: 16

## 📊 Results
- Training Accuracy: ~0.93  
- Validation Accuracy: ~0.81

## 📈 Visualization
The training and validation accuracy/loss were plotted to observe learning behavior and overfitting.

## 💬 Predict Custom Sentences
You can test any sentence using the `predict_bert_sentence.ipynb` notebook.


## ✅ How to Run
1. Mount Google Drive in Colab
2. Install dependencies (see `requirements.txt`)
3. Run `notebook/sentiment_bert.ipynb` to train
4. Use `test/predict_bert_sentence.ipynb` to predict

## ✨ Dependencies
See [`requirements.txt`](requirements.txt) for full list.


you can download the model and tokenizer from this link : https://drive.google.com/drive/folders/1eQGBDz8VDY01KgZ7LZsOi9Ue329DlB08?usp=sharing
