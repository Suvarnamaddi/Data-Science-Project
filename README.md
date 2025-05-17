Author: Suvarna Maddi
Domain: Data Science
Project Type: Mini Project / Learning Project

📘 About the Project
This is a simple Python project where I built an SMS spam classifier. The goal of this project is to take a text message as input and predict whether it is spam or ham (not spam). I used some basic NLP (Natural Language Processing) techniques to clean and process the data, and then used word frequencies to make predictions.

🎯 Aim
To develop a Python-based program that can classify text messages as spam or non-spam (ham) using basic data science and NLP techniques.

📊 Dataset Info
The dataset I used is called mail_data.csv.
It contains two columns:
Category → shows whether the message is spam or ham
Message → the actual content of the SMS


🔧 Tools & Libraries Used
Python 3
Pandas – for data handling
NLTK – for natural language processing (tokenizing, stopwords, etc.)
String – for punctuation handling


🧠 How the Classifier Works
Read the Dataset
Clean the Text
Lowercase conversion
Remove punctuation
Tokenize words
(optional: remove stopwords)
Count Words in Spam and Ham Messages

Prediction
User enters a message
The program checks how many words in the message are similar to spam/ham words from the dataset
It then predicts which one the message belongs to with a simple accuracy percentage


▶️ How to Run It
1.Clone this repository or download the files
2.Make sure you have the required libraries installed:
pip install pandas nltk
python sms_classifier.py
Please type a spam or ham message to check if our function prediction:
> Hey! Call now to win your free iPhone!
Message is Spam, with 88.88% accuracy


✅ What I Learned
How to use pandas to read and analyze data
Basics of text preprocessing (tokenization, punctuation removal)
How simple NLP techniques can be used for classification
How to use word frequency to make predictions

🚀 Future Improvements
Use machine learning models like Naive Bayes or SVM
Build a simple web app using Flask or Streamlit
Add visualization of common spam and ham words

📬 Feedback
This was a fun and educational mini-project. Any suggestions or improvements are welcome!
