# Term Project:

## Objectives:
  - Implement Homework 3 - but this time, predict rating instead of positive/negative. So, more classes and probabilities.

## Dataset: https://www.kaggle.com/jvanelteren/boardgamegeek-reviews

## Task: Implement predictor.

### Procedure:
  - Jupyter Notebook.
  - Pre-process and clean data and create vocabulary:
      - Remove special characters and extra spaces
      - Removing single characters - I and a. And others created due to removal of special characters
      - Lowercase all text
  - Train and Test split
  - Vectorizing the document, Remove the stop words
    - bag of words (word count vector)
    - tf-idf vector

  - Classifier Evaluation:
    - Linear regression
    - Naive Bayes

  - Hyper-Parameter tuning on Test results:
      - max_features= between 100 to 2000
      - combinations of bow/tf-idf and linear/naive-bayes
  - store best model and vectorizer.
  - Saving and Loading model and vectorizer.

### References:
https://stackabuse.com/text-classification-with-python-and-scikit-learn/
https://towardsdatascience.com/training-a-naive-bayes-model-to-identify-the-author-of-an-email-or-document-17dc85fa630a
https://www.kaggle.com/loryn808/baseline-bag-of-words-linear-regression
