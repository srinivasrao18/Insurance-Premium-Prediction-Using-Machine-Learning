# Insurance Premium Prediction System 🚀

This project is an end-to-end Machine Learning application that predicts insurance premiums based on user attributes such as age, BMI, lifestyle, and health-related factors.

The application uses a **segmented modeling approach**, where separate models are trained for different age groups (Young vs Rest population) to improve prediction accuracy.

A Streamlit web interface is provided for user interaction and real-time predictions.

---

## 📌 Project Features

* Data preprocessing and feature engineering
* Segmented machine learning models
* Separate scalers for different population groups
* Model selection based on user input
* Streamlit web application
* Production-ready modular code
* Saved trained models using joblib

---

## 🧠 Machine Learning Approach

The dataset was divided into two segments:

* **Young Model** → For younger age group customers
* **Rest Model** → For remaining population

Each segment uses its own trained model and scaler to provide more accurate premium predictions.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib

---

## 📂 Project Structure

```
.
├── artifacts/
│   ├── model_young.joblib
│   ├── scaler_young.joblib
│   ├── model_rest.joblib
│   └── scaler_rest.joblib
│
├── main.py                # Streamlit application
├── prediction_helper.py   # Model loading and prediction logic
├── requirements.txt       # Dependencies
└── README.md
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run Streamlit app

```
streamlit run main.py
```

---

## 🎯 Skills Demonstrated

* Machine Learning Model Development
* Data Segmentation Strategy
* Feature Engineering
* Model Deployment
* Streamlit Application Development
* Python Programming

---

## 🚀 Future Improvements

* Cloud deployment (AWS / Render / Azure)
* REST API integration using FastAPI
* Model performance monitoring

---

## 👤 Author

Mamidipelly Srinivas
LinkedIn: [Your LinkedIn URL](https://www.linkedin.com/in/mamidipellysrinivas/)
