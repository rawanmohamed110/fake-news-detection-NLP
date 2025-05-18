# 📰 Fake News Detection using NLP

This project uses (Natural Language Processing (NLP) and Machine Learning) techniques to detect whether a news article is **real or fake** based on its content.

The core goal is to preprocess text data, convert it into numerical features using TF-IDF or CountVectorizer, and train models like Logistic Regression or Naive Bayes to classify the news articles.

---

1- Project Files

- `nlp.fakenews.ipynb`: Main Jupyter Notebook with all code and results
- `dataset/` (optional): Contains `fake_news.csv` or a link to download it

---

2- Features

- Text preprocessing: lowercasing, stopword removal, stemming
- Feature extraction using:
  - CountVectorizer
  - TF-IDF Vectorizer
-Classification model:
    - Random Forest Classifier
- Model evaluation: accuracy, precision, recall, F1-score

---
3- Future Improvements
  -Optionally test other models like Logistic Regression or SVM for comparison
---

4- Dataset

If not included, download it from:
[Kaggle Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

Expected format (CSV):
- `title`, `text`, `label` columns  
- `label`: "REAL" or "FAKE"

---

5- How to Run

1. Clone/download this repo or upload it to your own GitHub.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.open jupyter notebook and run cells step by step
