# Malicious URL Detection System – Final Year Project

This repository contains the source code, datasets, and web app interface for my final year data science project. The objective is to classify URLs into four categories using machine learning, and to deploy a user-friendly detection system through a Streamlit web application.

---

## Project Objective

To build a multi-class classification system that can automatically detect and label URLs as:

- **Benign**
- **Defacement**
- **Phishing**
- **Malware**

This helps in identifying and preventing access to harmful or suspicious websites.

---

## Repository Structure

- `Malicious_URL_ML.ipynb`: Main notebook for data preprocessing, feature extraction, model training, and evaluation.
- `Streamlit/`: Code for the Streamlit app that allows users to test URLs in real time.
- `Visualization/`: Scripts and notebooks for EDA and visualizing model insights.
- `malicious_phish.csv`, `phishing_site_urls.csv`: Datasets used for training and testing the model.

---

## Machine Learning Approach

- **Model**: XGBoost Classifier  
- **Classification Type**: Multi-class (Benign, Defacement, Phishing, Malware)
- **Feature Engineering**: Extracted URL-based features (length, special characters, domain info, etc.)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score (per class)

---

## Streamlit Web App

The trained model is deployed through a Streamlit app, allowing users to input any URL and receive a real-time classification result.

### How to Run the App

```bash
cd Streamlit
streamlit run app.py
