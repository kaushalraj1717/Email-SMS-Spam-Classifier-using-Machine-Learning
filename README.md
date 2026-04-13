# 📧 Email / SMS Spam Classifier using Machine Learning & NLP

A Machine Learning web application that automatically classifies **Email or SMS messages** as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques and a trained classification model.

The system demonstrates the complete workflow of a real-world NLP project, including **data preprocessing, feature engineering, model training, and deployment using Streamlit**.

This project highlights practical skills in **Machine Learning, Text Processing, and Model Deployment**, making it suitable for **Data Science and Machine Learning portfolios**.

---

## Project Overview

Spam messages are a common problem in communication systems and can lead to **security risks and user inconvenience**.

This project uses **Machine Learning and Natural Language Processing (NLP)** to automatically detect spam messages based on text patterns and linguistic features.

The application allows users to **enter a message and instantly receive a prediction** indicating whether the message is spam or legitimate.

---

## Key Features

- Classifies messages as **Spam** or **Not Spam**
- Text preprocessing using NLP techniques
- Stopword removal and stemming
- Feature extraction using **TF-IDF Vectorization**
- Machine Learning-based prediction
- Interactive web interface using **Streamlit**
- Real-time message classification

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Streamlit  
- Pickle  
- Jupyter Notebook  

---

## Project Structure

Email-SMS-Spam-Classifier/
│
├── app.py # Streamlit web application
├── sms-spam-detection.ipynb # Model training and experimentation
├── model.pkl # Trained machine learning model
├── vectorizer.pkl # TF-IDF vectorizer
├── spam.csv # Dataset
└── README.md # Project documentation

## Model Workflow

The model follows a standard Natural Language Processing pipeline:

1. Data Cleaning  
2. Text Preprocessing  
3. Tokenization  
4. Stopword Removal  
5. Stemming  
6. Feature Extraction using TF-IDF  
7. Model Training  
8. Prediction  

---

## Text Preprocessing

The text data is processed using several NLP techniques to improve model performance.

These include:

- Converting text to lowercase  
- Tokenizing words using NLTK  
- Removing punctuation and special characters  
- Removing stopwords  
- Applying stemming using Porter Stemmer  

---

## Dataset

The dataset used in this project contains labeled SMS messages categorized into:

- **Spam**  
- **Ham (Not Spam)**  

This dataset is commonly used for spam detection tasks in **Machine Learning** and **Natural Language Processing**.

---

## Model Performance

The trained model achieves high accuracy in detecting spam messages.

**Example evaluation metrics:**

- Accuracy: **97%**  
- Precision: **1**   

> Update these values based on your actual model results.

---

## Application Interface

The Streamlit application provides a simple interface where users can:

- Enter an Email or SMS message  
- Click the **Predict** button  
- View the classification result instantly  

This demonstrates the deployment of a machine learning model into a usable web application.

---

## Future Improvements

- Add support for Email spam detection  
- Improve model accuracy with advanced algorithms  
- Add model comparison (Naive Bayes, Logistic Regression, SVM)  
- Deploy the application to cloud platforms  
- Enhance user interface design  

---
