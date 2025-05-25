# Fake News Prediction Model

Jupyter notebook with news prediction model

## Used data:
    https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

## Original kaggle link:
    https://www.kaggle.com/code/vsevolodvishnyakov/fake-news-prediction

## Installation

```bash
pip install -r requirements.txt
```

## Project Structure
- Fake.csv: database with fake news
- True.csv: databse with real news
- fake-news-predictions.ipynb: notebook

## About project
This project is a simple machine learning model that detects whether a news article is fake or real. It uses text data from two datasets labeled as fake and real news. The text is cleaned and processed by removing punctuation, stopwords, and lemmatizing words to make it easier for the model to understand.
The processed text is then converted into numerical features using TF-IDF vectorization. A logistic regression model is trained on this data to classify news articles as fake or real. The model’s performance is evaluated using accuracy, confusion matrix, and classification report.