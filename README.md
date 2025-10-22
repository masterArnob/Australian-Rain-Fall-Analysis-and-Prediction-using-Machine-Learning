# 🌦️ Australian Rainfall Analysis and Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow.svg)
![Scikit-learn](https://img.shields.io/badge/ML-ScikitLearn-orange.svg)
![Matplotlib](https://img.shields.io/badge/Viz-Matplotlib-green.svg)
![License](https://img.shields.io/badge/License-MIT-success.svg)

---

## 📘 Overview
This project focuses on **analyzing and predicting rainfall in Australia** using various **Machine Learning algorithms**.  
By leveraging weather data such as temperature, humidity, wind speed, and pressure, the model predicts whether it will **rain tomorrow**.

---

## 📂 Dataset
The dataset used in this project contains daily weather observations from multiple Australian weather stations.

- **Source:** [Australian Rainfall Dataset - Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- **Target Variable:** `RainTomorrow` (Yes / No)
- **Size:** ~145,000 records with 23 attributes

---

## ⚙️ Technologies Used
- **Python** 🐍
- **NumPy** & **Pandas** — Data manipulation  
- **Matplotlib** & **Seaborn** — Visualization  
- **Scikit-learn** — Machine Learning algorithms  
- **Jupyter Notebook** — Development environment  

---

## 🧠 Machine Learning Models
The following algorithms were tested and compared:

| Model | Description | Accuracy |
|-------|--------------|----------|
| Logistic Regression | Baseline classification model | 81% |
| Random Forest Classifier | Ensemble learning model | 86% |
| Decision Tree | Simple tree-based classifier | 82% |
| K-Nearest Neighbors | Distance-based classification | 78% |
| Support Vector Machine | Margin-based classification | 84% |

*(You can update these results based on your notebook outputs.)*

---

## 🧹 Data Preprocessing
1. Handling missing values  
2. Label encoding for categorical variables  
3. Feature scaling (StandardScaler / MinMaxScaler)  
4. Splitting dataset into training and testing sets  
5. Balancing target variable using `SMOTE` or undersampling (if imbalanced)

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/Australian-Rainfall-Prediction.git
cd Australian-Rainfall-Prediction
