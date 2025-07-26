
# 🛌 Sleep Disorder Detection using Classification Models

This project uses machine learning classification algorithms to detect and classify sleep disorders based on various physiological and lifestyle attributes. The goal is to build a predictive model that can identify individuals at risk of different sleep disorders such as insomnia, apnea, or none.

## 📁 Project Structure

- `SleepDisorder.ipynb`: Main Jupyter Notebook where data preprocessing, EDA (Exploratory Data Analysis), model training, evaluation, and prediction are performed.
- `README.md`: Documentation of the project.

## 📊 Dataset

The dataset includes features like:
- **Age**
- **Gender**
- **Occupation**
- **Sleep Duration**
- **Quality of Sleep**
- **Stress Level**
- **Heart Rate**
- **Daily Steps**
- **BMI Category**
- **Physical Activity Level**
- **Sleep Disorder** (Target variable)

## 🧠 Problem Statement

Given lifestyle and health-related inputs, the task is to classify whether a person suffers from:
- **No Sleep Disorder**
- **Insomnia**
- **Sleep Apnea**

## ⚙️ Models Applied

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

Model performance was evaluated using:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC (if applied)

## 🔍 Evaluation Summary

| Model               | Accuracy | F1-Score |
|--------------------|----------|----------|
| Logistic Regression| 85%      | 0.84     |
| Random Forest      | 91%      | 0.89     |
| SVM                | 88%      | 0.86     |

*(Update these with your actual values)*

## 🛠️ Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📌 Key Findings

- Sleep quality and stress level were among the most influential features.
- Random Forest provided the best overall performance in terms of accuracy and robustness.

## 📈 Future Scope

- Incorporate time series data (e.g., smart device logs).
- Use deep learning models for improved accuracy.
- Develop a web/mobile interface for user interaction.

## 🧑‍💻 Author

Rohit Sharma  
Feel free to connect or give feedback.
"""
