# Advanced Sentiment Analysis

This project implements a sentiment analysis pipeline using Natural Language Processing (NLP) techniques and machine learning models. It classifies text reviews into **positive** or **negative** sentiments.

## 🔍 Features

- Text preprocessing with NLTK (stopwords removal, lemmatization)
- Tokenization and vectorization using CountVectorizer
- Training sentiment classifier using Naive Bayes
- Evaluation with classification report and accuracy metrics

## 🧠 Algorithms & Tools

- Language: Python  
- Libraries: NLTK, Scikit-learn, Pandas, NumPy  
- Model: Multinomial Naive Bayes

## 🗃️ Dataset

A small sample dataset of text reviews with labeled sentiments (positive/negative). You can extend it with larger datasets such as:
- IMDb Reviews
- Twitter Sentiment datasets

## 🚀 How to Run

1. Clone the repository:
   ```
   git clone https://github.com/nandithgireesh/advanced-sentiment-analysis.git
   cd advanced-sentiment-analysis
   Install dependencies:
```
   pip install -r requirements.txt
   ```
   Run the notebook:
   Open Advanced_Sentiment_Analysis.ipynb in Jupyter Notebook or VSCode and run all cells.
   📊 Sample Output
   Accuracy: ~80% (on small sample dataset)

   Classification report showing precision, recall, and F1-score

   📌 Future Improvements
   Use of deep learning models (LSTM, BERT)

   Handling neutral sentiment

   Real-time sentiment prediction with a web interface
