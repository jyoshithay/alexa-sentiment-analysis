# Alexa Sentiment Analysis

This project predicts whether an Amazon Alexa product review is **Positive** or **Negative** using Machine Learning.  
The model is deployed using a Streamlit web app where users can enter a review and get an instant prediction.

## What This Project Does
- Cleans and preprocesses review text  
- Converts text into numerical features  
- Uses an XGBoost model to classify sentiment  
- Provides a Streamlit interface for real-time predictions  

## Files in This Repository
- **app.py** – Streamlit app for real-time prediction  
- **Alexa_Sentiment_Analysis.ipynb** – Notebook with EDA, preprocessing, and model training  
- **Alexa_Sentiment_Analysis_Report.docx** – Project report  
- **model_xgb.pkl** – Trained model  
- **countVectorizer.pkl** – Text vectorizer  
- **scaler.pkl** – Feature scaler  

## How to Run the App
1. Install the required libraries:
2. Run the Streamlit app:

## Example
**Input:**  
"The product works great and responds quickly."

**Output:**  
Positive

## Purpose
This project helps understand customer opinions and demonstrates end-to-end sentiment analysis using machine learning.


