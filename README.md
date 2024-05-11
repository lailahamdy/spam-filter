# Naive Bayes Classifier for Spam Filter - NLP Using PySpark

---

## Objective:
The objective of this project is to implement a spam filter using the Naive Bayes classifier within a Natural Language Processing (NLP) framework using PySpark. This classifier aims to accurately classify emails or text messages as either spam or not spam based on their content.

## Project Overview:
- **Naive Bayes Classifier:** This project utilizes the Naive Bayes algorithm for text classification. Naive Bayes is a probabilistic classifier that calculates the probability of a message being spam or not spam given the occurrence of certain words in the message.
- **PySpark:** PySpark is used as the framework for distributed data processing, allowing for efficient handling of large-scale datasets commonly encountered in NLP tasks.

## Steps:
### Preprocessing the Text
The preprocessing pipeline involves tokenizing the text, removing stop words, creating a count matrix, and computing TF-IDF scores to transform the raw text data into a numerical format suitable for model training.

### Model Training
Trained the Naive Bayes classifier using the preprocessed text data. Split the dataset into training and testing sets for model evaluation purposes. This involved fitting the model to the training data to learn patterns and associations between features and labels.

### Model Evaluation
Evaluated the performance of the trained model using appropriate metrics such as F1-score. Assessed how well the model generalized to unseen data.

### Prediction
Used the trained model to predict the class (spam or not spam) of new, unseen text messages or emails. This step applied the trained model to new data instances to make predictions on whether they were spam or not spam.
