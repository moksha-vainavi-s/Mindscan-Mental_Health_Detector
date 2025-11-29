# Mental Health Detector
This project predicts a person's mental health condition (such as depression level) using machine learning.
It analyzes lifestyle, emotional, and behavioral factors to classify mental health status.

## 📁 Files in This Project

* MENATL_HEALTH_DETECTOR_FINAL_PROJECT.ipynb – Main notebook containing data analysis, preprocessing, model building, and evaluation.

* Depression.csv – Dataset used for training and testing the model.

## 📊 What This Project Does

* Loads and explores the dataset

* Cleans, encodes, and preprocesses data

* Builds machine learning models

* Evaluates performance (Accuracy, Precision, Recall, F1 Score)

* Predicts mental health condition based on input features

## 🧠 Models Used

* Logistic Regression

* Random Forest

* Decision Tree

* KNN

## ▶️ How to Run the Project (Google Colab)

Upload both files to Google Colab:

* MENATL_HEALTH_DETECTOR_FINAL_PROJECT.ipynb

* Depression.csv

Install necessary libraries inside a Colab cell:

!pip install pandas numpy scikit-learn matplotlib seaborn

Run all cells in the notebook.


## 📌 Dataset Details

* The Depression.csv file includes features related to:

* Emotional state

* Sleep patterns

* Stress levels

* Lifestyle indicators

* Behavioral responses

* Target Column → Depression / Mental Health Level
  

## 🚀 Streamlit App

* Interactive web app built with Streamlit for mental-health prediction.

* Allows dataset loading, preview, and automatic feature detection.

* Supports training ML models (RF, LR, DT, KNN) directly in the UI.

* Shows evaluation metrics and confusion matrix after training.

* Provides a dynamic input form for users to get real-time predictions.


## 📊 Power BI Dashboard

This project includes a Power BI dashboard that visualizes key insights from the Mental Health Detection dataset. The dashboard helps understand patterns, trends, and factors associated with different levels of depression.

🔍 What the Power BI Dashboard Shows

* Overall distribution of depression levels (No Depression, Mild, Moderate, Severe)

* Behavioral and emotional patterns, including agitation, worthlessness, hopelessness, fatigue, and suicidal ideation

* Sleep quality and low-energy patterns across depression categories

* Comparison of symptoms and behavior frequency (Always, Often, Sometimes, Rarely, Never)

* Interactive charts for exploring how each factor relates to mental health status
