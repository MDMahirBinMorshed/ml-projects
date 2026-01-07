# Fake News Classification using NLP

## Overview
This project builds a machine learning model to classify news articles as **fake** or **real**
using Natural Language Processing (NLP) techniques.

## Dataset
- Source: Kaggle — Fake and Real News Dataset
- Two datasets were combined:
  - Fake news articles
  - Real news articles
- A binary label was manually assigned:
  - 0 = Fake
  - 1 = Real

## Methodology
1. Data loading and merging
2. Text cleaning and preprocessing
3. TF-IDF feature extraction
4. Logistic Regression model training
5. Model evaluation using accuracy and confusion matrix

## Results
- Accuracy: ~98%
- The model performs well in distinguishing fake and real news articles.

## Technologies Used
- Python
- Pandas
- scikit-learn
- Matplotlib
- Jupyter Notebook

## Future Improvements
- Use deep learning models (LSTM, BERT)
- Hyperparameter tuning
- Model deployment as an API
