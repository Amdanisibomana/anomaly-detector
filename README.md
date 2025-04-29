# 🚀 anomaly-detector

Anomaly Finder is a machine learning project focused on detecting unusual authentication activities.  
Through data exploration, system modeling, and anomaly detection, it uncovers patterns that could indicate potential security threats.

---

## 📚 Project Summary

- **Goal:** Analyze authentication data to detect suspicious activities using anomaly detection techniques.
- **Approach:** Data cleaning ➔ Exploratory Data Analysis (EDA) ➔ Model building ➔ Performance evaluation.

---

## 🗂 Dataset Details

| File | Description |
|:-----|:------------|
| **auth.csv** | Authentication event logs |
| **devices.csv** | Device-specific information |
| **orgs.csv** | Organizational details |
| **users.csv** | User profiles and metadata |

---

## 🔍 Workflow Overview

1. **Data Preparation:**  
   Cleaning and organizing the dataset for analysis.

2. **Exploratory Data Analysis (EDA):**  
   Studying success rates, device trends, authentication methods, and organizational usage.

3. **Model Implementation:**  
   Applying the Isolation Forest algorithm to detect anomalies.

4. **Model Evaluation:**  
   Measuring model effectiveness using accuracy, recall, precision, and F1-score.

---

## 📈 Key Insights

- The **authentication success rate** is approximately **60.17%**, with a failure rate near **39.83%**.
- **SMS authentication** showed the highest failure rate, suggesting a higher risk for security breaches.
- **Mobile devices** and **iOS systems** were the most commonly used for authentication attempts.
- The Isolation Forest model achieved **high recall** and **strong F1-scores**, indicating effective anomaly detection.

