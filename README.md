# System Threat Forecaster – Malware Infection Prediction

## 📌 Problem Statement
This project focuses on predicting the probability of malware infection on a system using telemetry data collected by antivirus software. Each system is uniquely identified and classified based on whether malware was detected.

This work is based on a Kaggle competition aimed at building reliable machine learning models for cybersecurity threat prediction.

---

## 📊 Dataset Overview
- Source: Kaggle – System Threat Forecaster
- Each row represents a unique machine (`MachineID`)
- Target variable:
  - `target = 1` → Malware detected
  - `target = 0` → No malware detected
- Dataset files are not included in this repository due to Kaggle data usage policies

---

## 🧠 Approach
1. Exploratory Data Analysis (EDA)
2. Handling missing values
3. Feature preprocessing and encoding
4. Model training and validation
5. Performance evaluation
6. Submission generation

---

## 🤖 Models Used
- Logistic Regression (baseline)
- Random Forest Classifier
- Gradient Boosting (if applicable)

---

## 📈 Evaluation Metric
- Accuracy Score (as defined in the competition)

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 📂 Project Structure
