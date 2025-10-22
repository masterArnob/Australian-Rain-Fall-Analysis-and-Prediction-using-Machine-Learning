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

| Model | Type | Accuracy |
|-------|------|-----------|
| Logistic Regression | Linear | 80% |
| Decision Tree | Non-linear | 82% |
| Random Forest | Ensemble | 85% |
| K-Nearest Neighbors | Distance-based | 78% |
| Support Vector Machine | Margin-based | 83% |
| Gradient Boosting | Ensemble | 86% |

> 🏆 **Best Model:** Gradient Boosting Classifier (86% accuracy)

---

## 📈 Evaluation Metrics

- Accuracy Score  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  

Model performance comparison visuals were created to determine the most reliable classifier.

---

## 🌦️ Insights & Findings

- **Humidity** was the strongest indicator of rainfall probability.  
- **Low pressure and high temperature** correlated with rainfall events.  
- **Random Forest and Gradient Boosting** outperformed simpler algorithms.  
- Feature correlation analysis helped identify key predictive attributes.

---

## 📄 Report & Visualization Previews

<p align="center">
  <a href="Assets/preview_report.png">
    <img src="Assets/preview_report.png" alt="Report Preview" width="300" style="border-radius:8px; margin-right:20px;">
  </a>
  <a href="Assets/preview_results.png">
    <img src="Assets/preview_results.png" alt="Results Preview" width="380" style="border-radius:8px;">
  </a>
</p>

<p align="center">
  <a href="Assets/preview_report.png" style="text-decoration: none; color: inherit;">
    <strong>📄 View Report</strong>
  </a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="Assets/preview_results.png" style="text-decoration: none; color: inherit;">
    <strong>📊 View Results</strong>
  </a>
</p>

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
├── Assets/
│   ├── preview_report.png
│   ├── preview_results.png
├── Australian Rain Fall Analysis and Prediction using Machine Learning.ipynb
├── requirements.txt
└── README.md
```

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
