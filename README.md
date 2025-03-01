# Sentiment Analysis on Amazon Reviews

## 📌 Project Overview

This project explores sentiment analysis on Amazon reviews using **Natural Language Processing (NLP)** techniques. We compare traditional **NLTK VADER** sentiment analysis with the more advanced **Hugging Face RoBERTa** transformer model.

## 📦 Dataset

The dataset consists of Amazon customer reviews labeled with star ratings (1 to 5). We preprocess and analyze these reviews to classify them into **positive, neutral, or negative sentiments**.

## 📊 Steps Covered in This Project

1.  **Import Dataset**
2.  **Exploratory Data Analysis (EDA)**
3.  **Sentiment Analysis using NLTK**
   -  Apply **NLTK's VADER** sentiment scoring
   -  Visualize sentiment distributions
4.  **Sentiment Analysis using Hugging Face RoBERTa**
   -  Use a **pre-trained transformer model** to classify sentiment
   -  Compare results with NLTK
5.  **Comparison of Model Performance**
   -  **Accuracy Evaluation** of both models
   -  **Analysis of misclassified reviews**
6.  **Using Hugging Face Pipelines for Sentiment Classification**

## 🛠 Tools & Technologies Used

- **Python** 
- **NLTK** (Natural Language Toolkit) 
- **Hugging Face Transformers** 
- **RoBERTa Pre-trained Model** 
- **Matplotlib & Seaborn** 

## 🔥 Key Findings

- **NLTK's VADER** performs well for short and simple texts but struggles with more complex sentiment structures.
- **Hugging Face's RoBERTa** achieves higher accuracy by understanding contextual nuances.
- **Misclassification analysis** helps in understanding where models fail and how they can be improved.

## 📢 Credits & References

- Dataset: [Kaggle](https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial)
- NLTK Sentiment Analysis: [NLTK Documentation](https://www.nltk.org/howto/sentiment.html)
- RoBERTa Model: [Hugging Face](https://huggingface.co/docs/transformers/model_doc/roberta)
