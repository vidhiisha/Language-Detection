# 🧠Language Detection using Natural Language Processing (NLP) and Machine Learning:
A machine learning project that predicts the language of a given text using Natural Language Processing (NLP) techniques.
This project demonstrates an end-to-end text classification workflow — from data cleaning and preprocessing to model training, evaluation, and custom prediction.

## 🔎Multi-Model Workflow for Language Detection:
This project uses text vectorization and the Multinomial Naive Bayes classifier to detect the language from a given text input.
It includes text preprocessing, feature extraction, and model evaluation to ensure high accuracy.

## 📊Dataset Information
Column Name     	       Description
Text	               The text sample input
Language	           The target language label
The dataset Language_Detection.csv contains multiple languages and text samples for training and testing.

## 🧠Key Features
### 🧹 Text Preprocessing
Removed special characters, numbers, and punctuation using Regex
Converted all text to lowercase
Encoded language labels using LabelEncoder
### 🧩 Feature Extraction
Converted text data into numerical form using CountVectorizer (Bag of Words)
### 🧮 Model Training
Model Used: Multinomial Naive Bayes
Split data into training and testing sets (80/20 ratio)
Trained the model and evaluated performance metrics
### 📈 Evaluation
Accuracy Score
Confusion Matrix
