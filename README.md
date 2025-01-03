# Fake-news-Detection-on-Hindi-Dataset

## Overview
Fake news is a pervasive problem in the digital age, influencing public opinion and causing misinformation on a massive scale. This project, TruthSeeker, focuses on building a reliable Fake News Detection System for Hindi news articles. The solution utilizes Natural Language Processing (NLP) techniques and machine learning models to classify Hindi news as either "Fake" or "Real."

![hindi_fake_news_architecture](https://github.com/user-attachments/assets/be3733c9-2d08-49ef-ab76-faf9f706ae1b)

## Features
### Language Support: 
Specifically designed to detect fake news in Hindi, addressing a critical need for regional language support.
### Machine Learning Model: 
Implements a trained model named FakeNews_Detection_in_hindi_dataset to classify news articles.
### User-Friendly Interface: 
Provides a Graphical User Interface (GUI) for non-technical users to easily input news text and receive results.
### Dataset Integration: 
Utilizes a preprocessed Hindi dataset of fake and real news articles.

# Representation of GUI


![WhatsApp Image 2025-01-03 at 22 19 42_73a2dc51](https://github.com/user-attachments/assets/d6ceb411-6a59-4185-8d86-027c2db525d9)

## Project Workflow

### Data Collection: 
Gathered a dataset containing labeled Hindi news articles (real and fake).
### Preprocessing: 
Cleaned the data to remove noise, such as punctuation, stopwords, and unnecessary symbols, while tokenizing Hindi text for further analysis.
### Feature Extraction: 
Applied vectorization techniques (e.g., TF-IDF or Count Vectorizer) to represent text in numerical format.
### Model Training: 
Trained an NLP-based classification model using algorithms like Logistic Regression, Naive Bayes, or Support Vector Machine.
### Model Evaluation: 
Assessed the model's accuracy, precision, recall, and F1 score to ensure robust performance.
### GUI Development: 
Built a user-friendly GUI to input and classify news articles interactively.

# Training loss of the Model


![Screenshot (13)](https://github.com/user-attachments/assets/3c6c84d1-44b0-4c2f-9181-49a359fc7465)


# Accuraccy of the Model

![Screenshot (14)](https://github.com/user-attachments/assets/6bab579a-1f59-47c0-af30-b766c355a43f)

## Future Scope
Enhance the dataset with more diverse examples to improve model generalization.
Implement deep learning models like LSTMs or Transformers (e.g., BERT for Hindi).
Add multilingual support for detecting fake news in other regional languages.
Develop a web-based interface for wider accessibility.
