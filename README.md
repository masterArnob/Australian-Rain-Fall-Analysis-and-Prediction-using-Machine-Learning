# 🌧️ Australian Rainfall Analysis and Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange)
![Pandas](https://img.shields.io/badge/Data%20Processing-Pandas-yellow)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)
![License](https://img.shields.io/badge/License-MIT-success)

---

## 🧩 Project Overview
Rainfall prediction plays a critical role in agriculture, water resource management, and disaster prevention.  
This project applies **machine learning techniques** to analyze weather data and predict the likelihood of **rainfall in Australia**.

By leveraging historical meteorological data such as temperature, humidity, wind speed, and atmospheric pressure, the project aims to build a **robust classification model** capable of forecasting whether it will rain tomorrow (`RainTomorrow`).

---

## 📊 Objectives
- Analyze trends and correlations in Australian weather data  
- Identify key features influencing rainfall patterns  
- Build and evaluate multiple machine learning models for classification  
- Compare model performances and interpret feature importance  
- Provide insights for data-driven weather forecasting

---

## 📂 Dataset Description
- **Dataset Name:** WeatherAUS  
- **Source:** [Kaggle - Australian Rainfall Prediction](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)  
- **Records:** ~145,460  
- **Features:** 23 (including `Rainfall`, `Humidity`, `WindGustSpeed`, `Pressure`, etc.)  
- **Target Variable:** `RainTomorrow` (Binary: Yes / No)

---

## ⚙️ Data Preprocessing Steps
1. **Missing Value Treatment:** Imputed or removed null entries in weather attributes.  
2. **Encoding:** Converted categorical variables (e.g., `WindGustDir`, `WindDir9am`) using `LabelEncoder`.  
3. **Feature Scaling:** Standardized numerical features for uniformity.  
4. **Data Balancing:** Addressed class imbalance using **SMOTE** (Synthetic Minority Oversampling Technique).  
5. **Train-Test Split:** Divided data into 80% training and 20% testing sets.

---

## 🤖 Machine Learning Models Implemented

| Model | Type | Purpose | Accuracy|
|-------|------|----------|--------------------|
| Logistic Regression | Linear | Baseline classification model | 80.61% |
| Decision Tree Classifier | Non-linear | Interpretability and feature analysis | 74.05% |
| K-Nearest Neighbors (KNN) | Distance-based | Simplicity and comparability | 79.69% |
| Support Vector Machine (SVM) | Margin-based | High-dimensional separation | 81.68% |

*(The best-performing model achieved ~86% accuracy on the test data.)*

---

## 📈 Model Evaluation Metrics
Each model was assessed using:
- **Accuracy Score**
- **Precision / Recall / F1-Score**
- **Confusion Matrix**
- **Classification Report**

---




---

## 💡 Future Enhancements
- Integrate **deep learning models (LSTM, GRU)** for temporal prediction.  
- Develop a **Streamlit web application** for real-time rainfall prediction.  
- Deploy the model as a **REST API** for integration with IoT weather sensors.  
- Perform **feature importance ranking** with SHAP or LIME for explainability.

---

## 👩‍💻 Author
**Your Name**  
📧 [your.email@example.com]  
🌐 [LinkedIn / Portfolio Link]  

---

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

