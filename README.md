# 🧬 Liver Disease Prediction using Machine Learning (ILPD)

> 🚀 A data-driven healthcare project that leverages Machine Learning to predict liver disease using clinical parameters from the **Indian Liver Patient Dataset (ILPD)**.

---

## 📌 Project Overview

Liver disease is a critical global health issue that requires early diagnosis for effective treatment. This project builds a **robust machine learning pipeline** to predict whether a patient is suffering from liver disease based on clinical attributes.

Using the **ILPD dataset**, we perform:

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Preprocessing
* ⚙️ Feature Engineering
* 🤖 Model Training & Comparison
* 📈 Model Evaluation & Optimization

---

## 📂 Dataset Information

* 📍 Source: UCI Machine Learning Repository
* 👥 Total Records: 583 patients
* 📊 Features: 10 clinical attributes + 1 target label

🎯 **Target Variable:**

* `1` → Liver Disease
* `0` → No Liver Disease

---

## 🔍 Exploratory Data Analysis (EDA)

We performed in-depth analysis to understand data distribution and relationships:

* 📈 Histogram plots for feature distribution
* 📦 Boxplots for outlier detection
* 🔥 Correlation heatmaps
* 📊 Feature vs target correlation analysis

---

## 🧹 Data Preprocessing

To prepare the dataset for modeling:

* ✅ **Categorical Encoding**
  * Gender → Binary encoding (Male = 1, Female = 0)
* ✅ **Missing Value Handling**
  * Mean Imputation applied
* ✅ **Feature Scaling**
  * Standardization using `StandardScaler`
* ⚖️ **Class Imbalance Handling**
  * Used `class_weight='balanced'` in Random Forest

---

## 🤖 Machine Learning Models

We trained and compared multiple classification algorithms:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost Classifier

---

## 📉 Evaluation Metrics

We evaluated models using:

* ✅ Accuracy
* ✅ Precision
* ✅ Recall
* ✅ F1 Score
* ✅ Confusion Matrix
* ✅ ROC Curve & AUC Score

---

## 🔁 Model Validation & Optimization

### 🔹 Cross-Validation

* Used **K-Fold Cross Validation (k=5)**
* Average Accuracy: **~71%**

### 🔹 Hyperparameter Tuning

* Applied **GridSearchCV**
* Optimized Random Forest parameters:

  * `n_estimators`
  * `max_depth`

---

## ⚖️ Impact of Preprocessing

We compared:

* 📉 Raw Data Model
* 📈 Preprocessed + Feature Engineered Model

💡 Result:

> Proper preprocessing and feature selection significantly improved model performance and stability.

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas, NumPy
* 📈 Matplotlib, Seaborn
* 🤖 Scikit-learn
* ⚡ XGBoost

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/liver-disease-prediction-ilpd.git
# Navigate to folder
cd liver-disease-prediction-ilpd
# Install dependencies
pip install -r requirements.txt
# Run notebook
jupyter notebook
```

---

## 🌟 Future Improvements

* 🔬 Deep Learning models (ANN, CNN)
* 🌐 Deploy as Web App (Flask/Streamlit)
* 📱 Real-time clinical prediction system
* 📊 Advanced feature selection techniques

---

## Conclusion

This project is more than just a machine learning pipeline — it’s a step toward **AI-driven healthcare solutions**. By combining data science with medical insights, we aim to contribute to **early detection and better diagnosis** of liver diseases.
---
