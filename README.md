# 🚀 Opportunity Status Prediction

This repository contains a machine learning project aimed at predicting the **Status Description** of opportunities based on various features.

🛠️ This code was developed as part of an **internship project** to practice and apply skills in data preprocessing, model training, evaluation, and feature interpretation.

---

## 📚 Libraries Used
- 🐼 pandas
- 🧮 numpy
- 📈 matplotlib
- 🎨 seaborn
- 🤖 scikit-learn

---

## 🔥 Project Workflow

1. **Load Dataset**  
   📂 Load a cleaned Excel dataset (`Cleaned_Opportunity_Data_With_Record_ID.xlsx`) containing opportunity data.

2. **Define Target Variable**  
   🎯 Target: `Status Description`

3. **Data Preprocessing**
   - 🗑️ Drop irrelevant columns like `Record ID`.
   - 🔤 Encode categorical features using `LabelEncoder`.
   - 🧹 Handle missing values using `SimpleImputer`.
   - 📏 Scale numerical features using `StandardScaler`.

4. **Model Training**
   - 📊 Logistic Regression
   - 🌳 Random Forest Classifier

5. **Model Evaluation**
   - 🏆 Accuracy scores
   - 📜 Classification report
   - 🔥 Confusion matrix visualization
   - 💡 Feature importance plot

6. **Visualization**
   - 📊 Heatmaps for confusion matrix and classification report
   - 📈 Bar plot for feature importances

---

## 🖼️ Visual Outputs

- ✅ Confusion Matrix for Random Forest
- ✅ Classification Report Heatmap
- ✅ Feature Importance Bar Chart

---
## 💡 Notes

This repository is made for learning and educational purposes only.  
Feel free to use the code by giving proper credits.

---

## 👨‍💻 Author

**Akshay CU**  
Data Engineer & AI Enthusiast

- GitHub: [https://github.com/akshaycu9093](url)
- LinkedIn: [https://www.linkedin.com/in/akshay-c-0a7106134/](url)

---

## 🌟 Future Improvements

-Improve Model Accuracy and Flexibility
Incorporate advanced algorithms like XGBoost or LightGBM, perform hyperparameter tuning, and allow users to switch between multiple models within the app.

-Enhance User Experience with Streamlit Features
Add interactive elements such as dropdowns, sliders, file upload options, and display prediction confidence, key metrics, and visual feedback like SHAP plots.

---

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-%E2%9D%A4-red)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)




