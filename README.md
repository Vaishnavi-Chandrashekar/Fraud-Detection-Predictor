# Fraud Detection Predictor App

## About the Project

Fraudulent financial transactions are a major issue for banks and digital payment platforms. This project was built to identify whether a transaction is **fraudulent or legitimate** using machine learning.

I worked on this project to understand how fraud detection systems function in real-world payment platforms and how machine learning models can help flag suspicious transactions quickly.

The project includes:

* **Data analysis and model building** in Jupyter Notebook
* A **trained machine learning pipeline** saved as a `.pkl` file
* A simple **Streamlit web app** where users can test transactions in real time

---

## Project Files

```bash
fraud-detection-project/
│── analysis.ipynb                  # Data cleaning, EDA, feature engineering, model training
│── fraud_detection.py              # Streamlit app
│── fraud_detection_pipeline.pkl    # Saved trained model
│── README.md                       # Project documentation
```

---

## What the App Does

The app allows users to enter transaction details such as:

* Transaction type
* Transaction amount
* Sender balance before and after transaction
* Receiver balance before and after transaction

Once the details are entered, the model predicts whether the transaction looks suspicious.

If fraud is detected → 🚨 alert message

If transaction looks normal → ✅ success message

---

## Tech Used

* Python
* Pandas
* Scikit-learn
* Joblib
* Streamlit
* Jupyter Notebook

## How It Works

1. The user enters transaction details
2. The input gets converted into a dataframe
3. The saved machine learning pipeline processes the input
4. The model predicts whether the transaction is fraudulent
5. The result is displayed instantly on the app

---

## Why I Built This

I wanted to build a project that combines:

* Machine learning
* real-world financial use cases
* model deployment
* user interaction through a simple interface

Instead of stopping at model training, I wanted to make the project usable through a web application.

---

## Future Improvements

* Improve model accuracy
* Add more fraud-related features
* Deploy online
* Build a dashboard for fraud analytics

## Streamlit - Preview
<img width="1920" height="989" alt="Streamlit output 1" src="https://github.com/user-attachments/assets/455acfb8-64fa-4e4e-bc4e-74ad0b3c7d55" />
<img width="1920" height="992" alt="Streamlit output 2" src="https://github.com/user-attachments/assets/2ff50911-c63d-4e02-bbdf-485b631c844e" />

