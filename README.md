# Sentiment_and_Topic_Analysis (E-commerce Project)

<b>Problem Statement</b>

*   Amazon is an online shopping website that now caters to millions of people everywhere. Over 4,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided. 
*   The dataset has attributes like brand, categories, primary categories, reviews.title, reviews.text, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted.
*   You are required to predict Sentiment or Satisfaction of a purchase based on multiple features and review text.

<b>Dataset Snapshot</b>

![picture](https://drive.google.com/uc?id=1h1pQG5ZlYAGS-lPncZUalh-duXfO1qsA)

**Project Task: Week 1**

**Class Imbalance Problem:**

1. Perform an EDA on the dataset.

  a)  See what a positive, negative, and neutral review looks like

  b)  Check the class count for each class. It’s a class imbalance problem.

2. Convert the reviews in Tf-Idf score.

3. Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.

**Project Task: Week 2**

**Tackling Class Imbalance Problem:**

1. Oversampling or undersampling can be used to tackle the class imbalance problem. 
2. In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this      project.
3. Use Tree-based classifiers like Random Forest and XGBoost.

**Project Task: Week 3**

**Model Selection:**

1. Apply multi-class SVM’s and neural nets.
2. Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB.
3. Assign a score to the sentence sentiment (engineer a feature called sentiment score).

**Project Task: Week 4**

**Applying LSTM:**

1. Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.)

2. Compare the accuracy of neural nets with traditional ML based algorithms.

3. Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral. 

  

**Tasks: Week 4**

**Topic Modeling:**

2. Perform Topic Modeling (LDA)

  
