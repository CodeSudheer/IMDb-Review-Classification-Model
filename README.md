This project involves building and evaluating machine learning models to classify IMDb movie reviews into positive or negative sentiments. The models are evaluated based on accuracy, AUC, and ROC curves, and the best model is selected for final use.

Table of Contents
  Project Overview
  Models Used
  Installation
  Data Preprocessing
  Model Evaluation
  Best Model Selection


Project Overview
This project aims to classify IMDb movie reviews into two sentiment categories: Positive and Negative. Three models were implemented and evaluated

  Logistic Regression
  Naive Bayes
  Random Forest
The models were trained using TF-IDF vectorized text data and tuned using cross-validation to ensure the best generalization.


Models Used
The following models were evaluated:
  Logistic Regression: A linear model used for classification that performs well in text classification tasks.
  Naive Bayes: A probabilistic model that works well for text classification, especially with word independence assumptions.
  Random Forest: A tree-based ensemble model used for classification tasks.


Installation
Prerequisites:
  Ensure you have the following libraries installed:
  Python 3.x
  scikit-learn
  pandas
  numpy
  matplotlib

Google Colab or Jupyter Notebook for running the code.
