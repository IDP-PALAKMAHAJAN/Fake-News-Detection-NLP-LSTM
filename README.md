# Fake-News-Detection-NLP-LSTM
Fake news classification using NLP preprocessing and LSTM neural networks in Python (TensorFlow).
# Fake News Detection using LSTM

## 📌 Project Overview
This project builds a deep learning model to classify news articles as **real or fake** based on their textual content. It uses **NLP preprocessing and LSTM (Long Short Term Memory) networks** for effective sequence learning.

## 📝 Key Steps
- Imported and merged fake and real news datasets
- Performed data cleaning (punctuation removal, stopwords removal, lowercasing)
- Visualized word clouds and class distributions
- Tokenized and padded text data for deep learning input
- Built an **LSTM-based model** using TensorFlow and Keras
- Achieved **~98% accuracy** on validation data

## 🔧 Tools and Libraries
- Python, Pandas, NumPy
- NLTK for NLP preprocessing
- Matplotlib and Seaborn for visualization
- TensorFlow and Keras for model building

## 💡 Key Learnings
- Sequence modeling with LSTM layers
- Text data preprocessing pipelines
- Binary classification in NLP using deep learning

## 📂 Dataset
- [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## 🚀 Future Improvements
- Use Bidirectional LSTM or GRU
- Implement attention mechanisms
- Deploy as an API for real-time classification
