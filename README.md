# Mental Health Detection using NLP

## Overview

This project is a Natural Language Processing (NLP) based machine learning system designed to identify potential mental health risks from social media text.

With the growing use of platforms like Twitter, individuals often express their emotions, stress, and mental state online. This system processes such textual data and classifies whether a given input indicates possible mental health concerns.

---

## Project Description

The project follows a standard NLP pipeline to transform raw text into meaningful insights:

- Performed text cleaning and preprocessing (removal of noise, stopwords)
- Applied tokenization and lemmatization techniques
- Converted text data into numerical features using TF-IDF vectorization
- Trained multiple machine learning models including Logistic Regression and Random Forest
- Evaluated model performance using standard classification metrics

Among the models tested, Logistic Regression achieved the best performance and was selected as the final model.

---

## Tech Stack

- Programming Language: Python  
- Libraries: Pandas, NumPy, NLTK, Scikit-learn  
- NLP Techniques: Text preprocessing, Tokenization, Lemmatization, TF-IDF  

---

## Dataset

https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset

## Results

- Accuracy: ~76%  
- ROC-AUC Score: ~0.85  

The model demonstrates a reasonable ability to distinguish between normal and potentially concerning text patterns.

---

## Future Improvements

- Implement deep learning models such as LSTM or BERT for improved context understanding  
- Develop a web-based interface for real-time predictions  
- Integrate with live social media data sources  

---

## Author

Thottempudi Lakshmi Tejaswi  
GitHub: https://github.com/Tejaswi154
