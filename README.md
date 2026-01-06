#NLPFinal
Sentiment Analysis of Amazon Electronics Reviews (Electronics_5 dataset) using NLP and classical machine learning models.

#Sentiment Analysis of Amazon Electronics Reviews (Electronics_5)

#Project Overview  
This project implements a Natural Language Processing (NLP) pipeline to analyze customer sentiment in Amazon Electronics product reviews. Reviews are categorized into three sentiment classes: Negative, Neutral, and Positive, using TF-IDF feature extraction and classical machine learning models.

#Dataset  
The project uses the Amazon Electronics Reviews dataset (Electronics_5.json), which is part of the Amazon Product Review Dataset (5-core).

Due to the large file size (~1.37 GB), the dataset is not uploaded to this repository.

Dataset source (reference Kaggle notebook):  
https://www.kaggle.com/code/shivamparab/amazon-electronic-reviews

The notebook assumes the dataset file is named:  
Electronics_5.json

#Methodology  
1. Data loading and exploratory data analysis  
2. Text preprocessing (cleaning, tokenization, stemming, lemmatization)  
3. TF-IDF feature extraction  
4. Sentiment label creation based on star ratings  
5. Model training using:
   - Multinomial Naive Bayes  
   - Logistic Regression  
6. Model evaluation using accuracy, classification report, and confusion matrix  
7. Bigram frequency analysis and Part-of-Speech (POS) tagging  

#Tools and Libraries  
- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib  

#How to Run  
1. Open IT9002_NLP_Project.ipynb in Google Colab or Jupyter Notebook.  
2. Place Electronics_5.json in the same directory.  
3. Run the notebook cells sequentially.

Course Information  
Course: IT9002 - Natural Language Processing  
Program: MSc Artificial Intelligence  
