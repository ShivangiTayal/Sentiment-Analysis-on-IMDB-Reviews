📌 Project Overview

This project focuses on building a Sentiment Analysis model to classify IMDB movie reviews as positive or negative using Natural Language Processing (NLP) techniques and Machine Learning models.

📂 Dataset

Dataset: IMDB Movie Reviews (10,000 samples)

Contains text reviews labeled as positive or negative.

🔑 Approach

Data Preprocessing

Removed HTML tags, converted text to lowercase.

Removed stopwords, applied stemming using PorterStemmer.

Tokenized text and reconstructed sentences.

Feature Extraction

Used CountVectorizer (Bag-of-Words, 500 features) to convert text into numerical format.

Modeling

Trained Naïve Bayes classifiers: GaussianNB, MultinomialNB, BernoulliNB.

Compared their performance.

Evaluation

Measured accuracy, precision, recall, and F1-score.

Best accuracy achieved: ~85%.

📊 Results

Sentiment distribution visualized with Matplotlib/Seaborn.

Naïve Bayes variants showed strong performance, MultinomialNB worked best with text data.

🛠️ Tech Stack

Python, NLP, Scikit-learn, NLTK, Matplotlib, Seaborn
