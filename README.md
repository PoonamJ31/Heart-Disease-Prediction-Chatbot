# 🫀 Heart Disease Prediction Chatbot

An interactive web-based chatbot built using Streamlit to predict the risk of heart disease based on clinical inputs. This project showcases an end-to-end machine learning pipeline, from data preprocessing and model training to deployment via Streamlit Cloud.

## 🚀 Project Overview

This chatbot allows users to input key health indicators and receive real-time predictions on the likelihood of heart disease. It's designed to demonstrate how machine learning can support early risk detection in healthcare through accessible technology.

## 💡 Key Features

- Interactive chatbot interface using **Streamlit**
- Real-time predictions using a **Random Forest Classifier**
- Preprocessing and feature engineering for better model accuracy
- **End-to-end deployment** on Streamlit Cloud

## 🧠 Machine Learning Pipeline

- Data preprocessing (handling missing values, encoding, scaling)
- Feature selection based on domain knowledge
- Model training using Random Forest
- Model serialization using `joblib`
- Web integration with Streamlit

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas, NumPy
- Joblib
- Streamlit Cloud (for deployment)

## 🌐 Live Demo

🔗 [Try the Chatbot](https://heartdiseasepredictionchatbot.streamlit.app/)

## 📁 Project Structure
 heart-disease-prediction-chatbot/
 
├── app.py # Streamlit app script

├── cardio_pipeline.pkl # Trained model

├── requirements.txt # Project dependencies

└── .streamlit/

└── secrets.toml # Streamlit configuration

