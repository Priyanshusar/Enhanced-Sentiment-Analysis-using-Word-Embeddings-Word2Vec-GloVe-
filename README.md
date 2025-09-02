# Enhanced-Sentiment-Analysis-using-Word-Embeddings-Word2Vec-GloVe-

# Project Overview

This project explores the use of word embeddings (Word2Vec and GloVe) to analyze customer reviews and predict sentiment. Unlike traditional TF–IDF models, word embeddings capture semantic meaning and contextual similarity, providing a more powerful representation of text.

The workflow includes data preprocessing, embedding generation, model training, evaluation, and comparison of Word2Vec and GloVe approaches.

# Problem Statement

Customer reviews hold valuable insights about product performance and customer satisfaction. Traditional feature engineering methods may fail to capture the contextual meaning of words.
This project leverages Word2Vec and GloVe embeddings to build sentiment classifiers that better understand natural language and improve prediction accuracy.

# Objectives

Preprocess raw text data from customer reviews.

Generate vector representations using Word2Vec and GloVe.

Train machine learning models (Random Forest and others) on embeddings.

Compare the performance of embedding-based models with traditional methods.

Provide insights into which embedding method is more effective for sentiment classification.

# Methodology

Dataset Preparation: Import and clean product reviews.

Text Preprocessing: Tokenization, stopword removal, stemming/lemmatization.

Embedding Generation:

Word2Vec: Trained on the corpus to create custom embeddings.

GloVe: Pre-trained embeddings applied for richer context.

Modeling: Random Forest and other classifiers trained on embeddings.

Evaluation: Accuracy, F1-score, and confusion matrix used for comparison.

Analysis: Assess embedding effectiveness in capturing sentiment context

# Results

Word2Vec and GloVe embeddings significantly improved classification accuracy compared to traditional Bag-of-Words.

Random Forest with embeddings performed strongly, though Word2Vec and GloVe had differences in capturing context.

Embedding-based models demonstrated the ability to generalize better on unseen text.
