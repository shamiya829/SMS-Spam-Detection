# SMS-Spam-Detection

# Spam SMS Identification Using Supervised Machine Learning and NLP

## Overview
This project aims to develop a robust SMS Spam Detection Model using supervised machine learning and natural language processing (NLP) techniques. By accurately classifying incoming messages as spam or legitimate, the model enhances user security, privacy, and overall communication experience. 

## Contributors
- Katie Shih
- Mireya Saldivar
- Naomi Ichiriu
- Shamiya Lin

## Course Information
- Course: I 310D: Introduction to Human-Centered Data Science
- Instructor: Professor Abhijit Mishra
- Institution: School of Information, The University of Texas at Austin
- Date: May 6, 2024

## Introduction
Spam messages pose a significant challenge in today's digital age, resulting in annoyance, potential security threats, and privacy breaches. To combat this issue, this project utilizes a Naive Bayes machine learning algorithm for spam detection. By preprocessing a dataset from Kaggle, the model is trained and evaluated to differentiate between spam and non-spam messages.

## Data Description
The SMS Spam Collection Dataset from Kaggle is utilized, comprising labeled text messages categorized as spam or legitimate (ham). The dataset contains 5,574 English messages with attributes for message classification and content. This imbalance allows the model to learn effectively and generalize well to unseen data.

## Methodology
The methodology involves preprocessing the dataset by converting text to lowercase and tokenizing messages. NLTK's Word Tokenize is used for tokenization. The dataset is then split into training and testing sets (20% and 80%, respectively). CountVectorizer from Scikit-learn is employed for vectorization, converting raw text into numerical data for the Naive Bayes model. Naive Bayes operates on the principle of conditional probability, discerning patterns within text data to classify messages as spam or ham.

## Results
The model achieves consistently high accuracy scores (0.97 to 0.99) across multiple test runs. Precision, recall, and F1 scores also indicate the model's effectiveness in minimizing errors and accurately classifying messages. Example test runs demonstrate the model's ability to differentiate between spam and ham messages with minimal errors.

## Conclusion
The project successfully addresses the challenge of spam messages in mobile communication through the development of a robust SMS Spam Detection Model. High accuracy, precision, recall, and F1 scores underscore the model's reliability and potential to enhance user security and privacy. Further enhancements and real-world implementations are suggested for improving the model's effectiveness.

## References
- Menzli, A. (2023, August 11). Tokenization in NLP: Types, challenges, examples, tools. neptune.ai.
- Sarreal, R. (2023, September 2). How to avoid the no. 1 text message scam putting your money at risk. Los Angeles Times.
- What are naïve Bayes classifiers?. IBM. (2024, April 8).

This documentation provides an overview of the project, including its objectives, methodology, results, and conclusions. It serves as a comprehensive resource for understanding and replicating the project's process and outcomes.
