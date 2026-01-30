# Spam Mail Classification

This project classifies messages as **Spam** or **Not Spam (Ham)** using machine learning.

## Problem Statement
Spam messages are unwanted and can be harmful.  
This project builds a model that automatically detects whether a message is spam or not.

## Dataset
- SMS/Email text data
- Labels: `spam` or `ham`
- Dataset loaded directly from an online source

## Approach
- Text preprocessing using CountVectorizer
- Converted text messages into numerical features
- Trained a Naive Bayes classifier
- Evaluated the model using accuracy score

## Results
- Achieved approximately **98% accuracy**
- Successfully classified custom test messages
- Spam messages like prize offers were correctly detected

## Example
Input: "Congratulations! You won a free cash prize. Click now!"

Output: Spam

Input: "Wanted to meet you tomorrow"

Output: ham


## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

## Conclusion
This project demonstrates how machine learning and text processing can be used to effectively detect spam messages.


