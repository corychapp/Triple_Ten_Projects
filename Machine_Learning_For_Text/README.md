# Film Junky Union - Machine Learning for Text: LLM, BERT

## Introduction
In this project for Film Junky Union, a vibrant community for classic movie enthusiasts, the goal is to train a model capable of automatically detecting negative movie reviews. The mission involves developing a system for filtering and categorizing movie reviews within this edgy community.

### Details of Large Language Model
The project utilizes frameworks such as scikit-learn and regular expressions, employing label encoding for preprocessing. Additionally, NLTK is utilized for tokenizing language, and Term Frequency-Inverse Document Frequency (TF-IDF) is employed to determine frequency relevancy. Advanced language models like BERT and spaCy are also integrated into the process.

## The Data
A dataset consisting of IMDB movie reviews with polarity labeling is used to build a model for classifying reviews as either positive or negative.

## Results
The model successfully distinguishes between positive and negative reviews, aiming for an F1 score of at least 0.85 for accuracy. It is noted that the model encounters slight difficulties with sarcasm, a challenge that is also faced by humans.
