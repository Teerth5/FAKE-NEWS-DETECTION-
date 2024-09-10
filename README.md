# FAKE-NEWS-DETECTION-


Fake News Detection - A Machine Learning Approach
This project explores building a model to classify news articles as real or fake. Here's a summary of the workflow and methodology:

Data Acquisition and Preprocessing:

Fake and real news datasets are loaded in CSV format.
Data is cleaned by converting text to lowercase, removing punctuation, extra spaces, URLs, and HTML tags.
A "class" label is assigned (0: Fake, 1: Real) to each article.
Techniques used: Pandas for data manipulation, regular expressions for text cleaning.
Feature Engineering and Model Training:

Text data is converted into numerical features using TF-IDF vectorization.
The data is split into training and testing sets.
Three machine learning models are trained:
Logistic Regression (LR)
Multinomial Naive Bayes (MB)
Gradient Boosting Classifier (GBC)
Techniques used: Scikit-learn library for data splitting, TF-IDF vectorization, and model training.
Model Evaluation:

The models' performance is evaluated using accuracy score and classification report (precision, recall, F1-score) on the testing data.
Manual Testing:

A function allows users to input a news article for manual classification by the trained models.
Overall, this project demonstrates a basic framework for building a fake news detection system using techniques like data cleaning, feature engineering, and various machine learning algorithms.

Note: This is a simplified example, and more advanced techniques may be needed for real-world applications.
