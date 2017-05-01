# ISYE6740-Project
This project is applying several word embedding methods on Reddit news headlines to predict change in stock market.

## Data Source
Kaggle data page:
https://www.kaggle.com/aaron7sun/stocknews

We mainly used two data files:
1. Combined_News_DJIA.csv --- used to do feature engineering
2. DJIA_table.csv --- used DJIA score for auto regression

## Jupyter Notebook Files
* CSE6740Project-BagOfWords.ipynb: 
Preprocessed text data with **bag of words** and **TF-IDF**.
Trained using linear SVM, logistic regression (LR), random forest (RF), adaboosting (AD) and Naive Bayes (NB).

* ISYE6740Project-W2V.ipynb: 
Preprocessed text data with **word2vec** and trained using LR, RF,  Bernoulli Naive Bayesian (BNB) and K-Nearest Neighbours (KNN).

* isye6740_topic_modelling.ipynb: 
Preprocessed text data with **topic modeling** and trained using LR, SVM, RF, gradient boosting (GB) and KNN. 

## Authors
**Hanying Chen, Ningqin Liu, Chongchao Zhao, Shiting Zhu** 

