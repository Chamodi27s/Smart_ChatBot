# Article-Based Chatbot

This is a simple chatbot built using Python that reads an online article using the `newspaper3k` library and responds to user queries based on the content of the article. It uses Natural Language Processing (NLP) techniques including tokenization, bag-of-words, and cosine similarity to find the most relevant response.

## 📌 Features

- Scrapes and summarizes online articles
- Uses NLTK for tokenizing text
- Calculates similarity between user input and article content
- Responds with the most relevant sentence
- Built to run in Google Colab

## 🔧 Requirements

- Python 3.x
- newspaper3k
- nltk
- scikit-learn
- numpy

## 🚀 Installation

In Google Colab, run:

```python
!pip install newspaper3k
!pip install lxml_html_clean
import nltk
nltk.download('punkt')
