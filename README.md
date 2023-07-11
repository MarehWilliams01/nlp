# README.md

This README file provides a brief overview of the approach taken, the main findings, and any challenges encountered in this project.

## Approach

The data was preprocessed by removing all punctuation, symbols, and stop words. Lemmatization was then performed to group together similar words with the same meaning. Count Vectorization and TF-IDF transformers were then applied to the data to convert it into a format that could be used by the machine learning algorithms.

## Main Findings

The highest accuracy was achieved using the MultinomialNB algorithm, with an accuracy of 79.6%. The LinearSVC and RidgeClassifier algorithms achieved accuracies of 78.2% and 78.8%, respectively.

## Challenges

The main challenges encountered were in preprocessing the data. The data was not cleaned in any way, so there was a lot of noise that had to be removed. Additionally, the accuracy of the model could not be increased beyond 79.6%, even after trying different algorithms.


