# Sentiment-Analysis-of-Product-Reviews-using-BERT

This repository contains a project focused on analyzing the sentiment of product reviews using a BERT-based model. The project aims to classify product reviews with 1 - 5 star rating, providing insights into customer opinions.

![sent](https://github.com/MininduLiyanage/Sentiment-Analysis-of-Product-Reviews-using-BERT/assets/73852035/25a169b6-58f3-488b-8ade-023d39612da4)


## Model

**bert-base-multilingual-uncased-sentiment**
This is a [bert-base-multilingual-uncased model](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment?text=mehh) finetuned for sentiment analysis on product reviews in six languages: English, Dutch, German, French, Spanish, and Italian. It predicts the sentiment of the review as a number of stars (between 1 and 5).

This model is intended for direct use as a sentiment analysis model for product reviews in any of the six languages above or for further finetuning on related sentiment analysis tasks.


## Web Scraping:

BeautifulSoup: Used for parsing HTML and extracting review content.

re (Regular Expressions): Employed for pattern matching and cleaning extracted text.

requests: Facilitates HTTP requests to fetch web pages containing product reviews.

