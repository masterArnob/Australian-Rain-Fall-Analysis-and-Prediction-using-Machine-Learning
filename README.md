# 🌦️ Australian Rainfall Analysis and Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow.svg)
![Scikit-learn](https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange.svg)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📖 Project Overview

This project focuses on analyzing **Australian rainfall patterns** and predicting the likelihood of rain using **machine learning algorithms**.  
The model aims to assist in **weather forecasting**, **agriculture planning**, and **climate research** through data-driven insights.

Key objectives include:

- Understanding weather trends across Australia  
- Identifying key factors influencing rainfall  
- Building and comparing multiple ML models  
- Improving prediction accuracy for `RainTomorrow`  

---

## 📊 Dataset Overview

- **Dataset Name:** WeatherAUS  
- **Source:** [Kaggle - Australian Rainfall Prediction](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)  
- **Records:** ~145,460  
- **Features:** 23 (e.g., Temperature, Humidity, WindSpeed, Pressure, Rainfall, etc.)  
- **Target Variable:** `RainTomorrow` (Binary: Yes / No)

---

## 🧹 Data Preprocessing (Python)

- ✅ Removed or imputed missing values  
- ✅ Encoded categorical variables using `LabelEncoder`  
- ✅ Scaled numeric features for model consistency  
- ✅ Balanced the target variable using `SMOTE`  
- ✅ Split dataset into training (80%) and testing (20%) sets  

---

## 🤖 Machine Learning Models Implemented

| Model | Accuracy |
|-------|-----------|
| Logistic Regression | 80.61% |
| Decision Tree | 74.05% |
| Random Forest | 81.68% |
| K-Nearest Neighbors | 79.69% |
| Support Vector Machine | 81.68% |

> 🏆 **Best Model:** Random Forest and SVM (81.68% accuracy)

---

## 📈 Evaluation Metrics

- Accuracy Score  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Classification Report

Model performance comparison visuals were created to determine the most reliable classifier.

---







---

## 💡 Future Enhancements

- Incorporate **Deep Learning models (LSTM, GRU)** for time-series forecasting  
- Build an interactive **Streamlit dashboard** for rainfall prediction  
- Integrate **real-time weather API** data sources  
- Perform **SHAP analysis** for feature explainability  

---

## 👨‍💻 Author

**Sadmanul Hoque**  
📧 sadmnulhoque21@gmail.com  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/sadmanul-hoque/)  
💾 [GitHub Profile](https://github.com/masterArnob)

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

### ⭐ If you found this project insightful, consider giving it a star!
