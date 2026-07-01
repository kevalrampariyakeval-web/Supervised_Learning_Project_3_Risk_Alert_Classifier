# 🛡️ Risk Alert Classifier
 
A machine learning project that predicts whether a case is **"Risky"** or **"Not Risky"** based on given data. The goal is to build a system that can catch risky cases early, so alerts can be raised before things go wrong.
 
## 📌 About the Project
 
Risk detection is an important problem in many fields like finance, security and fraud prevention. Missing a risky case (a false alarm going unnoticed) can be costly, so this project focuses not just on accuracy, but also on catching as many real risks as possible.
 
This notebook walks through a complete machine learning pipeline — from raw data to a final tuned model — in a clear, step-by-step way. Every code cell also has a short **Intuition** note below it, explaining what that step is doing in simple words. So even if you're a beginner, you can follow along easily. 🙂
 
## 🔍 What's Covered
 
- **🧹 Data Cleaning** — handling missing values and removing duplicate records
- **📊 Exploratory Data Analysis** — checking data shape, stats, target distribution, feature distributions and correlations
- **🔢 Encoding** — converting text (categorical) columns into numbers
- **🩹 Missing Value Imputation** — using KNN Imputer to smartly fill gaps
- **⚖️ Handling Imbalanced Data** — comparing Random Under Sampling, Random Over Sampling, SMOTE and ADASYN
- **🤖 Model Building** — training Logistic Regression, Decision Tree and Random Forest classifiers
- **📈 Model Evaluation** — using Accuracy, Precision, Recall, F1-Score and Confusion Matrix
- **🎯 Error Analysis** — understanding Type-I (false alarm) and Type-II (missed alarm) errors
- **🛠️ Hyperparameter Tuning** — improving the Random Forest model using RandomizedSearchCV and GridSearchCV
- **📉 ROC Curve & AUC Score** — visually and numerically comparing model performance
- **🏆 Final Model Selection** — picking the best performing model based on F1-Score
## 🎯 Why This Matters
 
A good risk classifier isn't just about high accuracy — it's about balance. A model that misses too many risky cases (high Type-II error) can be dangerous, while one that raises too many false alarms (high Type-I error) becomes annoying and less trusted. This project explores that balance in depth, using multiple models and balancing techniques to find the best trade-off.
 
## 🧰 Tech Stack
 
- **Python** 🐍
- **Pandas & NumPy** — data handling
- **Matplotlib & Seaborn** — visualization
- **Scikit-learn** — machine learning models & evaluation
- **Imbalanced-learn** — handling class imbalance (SMOTE, ADASYN, etc.)
## ✨ Highlights
 
- Beginner-friendly notebook with **Intuition** notes after every code cell 📝
- Multiple balancing techniques compared side by side ⚖️
- Multiple models compared side by side 🤝
- Hyperparameter tuning for improved performance 🚀
- Clear visualizations for confusion matrices and ROC curve 📊
 
