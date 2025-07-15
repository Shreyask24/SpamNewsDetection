# Spam News Detection using Machine Learning

This project is a Machine Learning-based model that detects whether a news headline is **genuine** or **fake** using NLP and text classification techniques. Built using Python, it leverages **TF-IDF vectorization** and the **Multinomial Naive Bayes** algorithm.

## Features

- Preprocessing of text data using NLTK
- Feature extraction with **TF-IDF**
- Accuracy evaluation on test and training sets
- CLI-based prediction for user-input news headlines

> Each entry contains a news `title` and a manually added label:  
> `0` = Real news, `1` = Fake news

## Model Overview

- **Text Preprocessing**: Lowercasing, removing special characters, stopword removal, lemmatization.
- **Vectorization**: TF-IDF with bi-grams, max 50,000 features.
- **Classification Model**: Multinomial Naive Bayes from `sklearn`.

## Tech Stack

- Python 3
- Pandas, NumPy
- NLTK
- Scikit-learn

## Accuracy

- Achieved **~90-92%** accuracy on test and training data.

## How to Run
   ```bash
   git clone https://github.com/Shreyask24/SpamNewsDetection.git
   cd SpamNewsDetection
   pip install -r requirements.txt
   python spam_news_detector.py

Enter News: Elon Musk launches new AI project
Output: News is correct!
```

