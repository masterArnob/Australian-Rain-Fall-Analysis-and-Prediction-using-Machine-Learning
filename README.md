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

| Model | Type | Purpose | Accuracy (Approx.) |
|-------|------|----------|--------------------|
| Logistic Regression | Linear | Baseline classification model | 80% |
| Decision Tree Classifier | Non-linear | Interpretability and feature analysis | 82% |
| Random Forest Classifier | Ensemble | Improved performance and robustness | 85% |
| K-Nearest Neighbors (KNN) | Distance-based | Simplicity and comparability | 78% |
| Support Vector Machine (SVM) | Margin-based | High-dimensional separation | 83% |
| Gradient Boosting | Ensemble | Optimal bias-variance tradeoff | 86% |

*(The best-performing model achieved ~86% accuracy on the test data.)*

---

## 📈 Model Evaluation Metrics
Each model was assessed using:
- **Accuracy Score**
- **Precision / Recall / F1-Score**
- **Confusion Matrix**
- **ROC-AUC Curve**

Visual comparisons were made between models to identify performance trade-offs and optimal hyperparameters.

---

## 🔬 Insights and Findings
- **Humidity and Rainfall:** High humidity levels (>80%) strongly correlate with rainfall events.  
- **Wind Direction:** Sudden shifts in wind gust direction often precede rainfall.  
- **Temperature & Pressure:** Low pressure and high temperature variations are leading predictors.  
- Ensemble models like **Random Forest** and **Gradient Boosting** consistently outperformed simpler models.

---

## 🧠 Technologies and Tools Used
| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python (3.9+) |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Balancing | imbalanced-learn (SMOTE) |
| Development | Jupyter Notebook |

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Australian-Rainfall-Prediction.git
cd Australian-Rainfall-Prediction
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
```bash
jupyter notebook "Australian Rain Fall Analysis and Prediction using Machine Learning.ipynb"
```

---

## 📁 Project Structure
```
├── data/
│   └── weatherAUS.csv
├── Australian Rain Fall Analysis and Prediction using Machine Learning.ipynb
├── requirements.txt
└── README.md
```

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

### ⭐ If you found this project useful, please give it a star and share it with others!
