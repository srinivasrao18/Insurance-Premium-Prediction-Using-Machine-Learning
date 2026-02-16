# Insurance Premium Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting insurance premiums using machine learning techniques based on customer demographic and health-related attributes.

A key feature of this project is **data segmentation**, where separate models are trained for different customer groups to improve predictive performance.

## 🚀 Features

* Data preprocessing and cleaning
* Customer segmentation (Young vs Rest population)
* Feature scaling and transformation
* Machine learning model training and evaluation
* Separate trained models saved using joblib
* Modular and production-ready structure

## 🧠 Machine Learning Approach

The dataset was divided into segments based on age groups to capture different risk patterns:

* Young Model
* Rest Population Model

Each segment uses its own scaler and trained model to improve accuracy.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Jupyter Notebook

## 📂 Project Structure

```
project/
│
├── artifacts/
│   ├── model_young.joblib
│   ├── scaler_young.joblib
│   ├── model_rest.joblib
│   └── scaler_rest.joblib
│
├── young_model.py
├── rest_model.py
├── predict.py
├── data_segmentation.ipynb
└── README.md
```

## ⚙️ How to Run

1. Clone the repository

```
git clone <your-repo-link>
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run prediction

```
python predict.py
```

## 📊 Skills Demonstrated

* Machine Learning Model Development
* Data Segmentation Strategy
* Feature Engineering
* Model Evaluation
* Production Workflow
* Python Programming

## 🎯 Future Improvements

* API deployment using FastAPI/Flask
* Web interface integration
* Cloud deployment

## 👤 Author

Your Name
LinkedIn: <your-link>
