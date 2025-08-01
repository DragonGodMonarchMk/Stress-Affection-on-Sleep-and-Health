# Stress-Affection-on-Sleep-and-Health
This project investigates the impact of stress on sleep quality and overall health using exploratory data analysis and machine learning. Leveraging a structured dataset, we analyze how lifestyle, stress levels, and habits influence sleep health and predict outcomes using classification models. 
# 🧠 Stress, Sleep, and Health: A Data Science Approach

This project explores how stress affects sleep patterns and health by analyzing a lifestyle dataset. It applies data visualization, preprocessing, and machine learning classification techniques to uncover correlations and predict health conditions related to sleep and stress.

---

## 📁 Project Structure

📦 stress-sleep-health-analysis/
├── stress-affection-on-sleep-and-health.ipynb
├── Sleep_health_and_lifestyle_dataset.csv
├── README.md
└── requirements.txt
---

## 📊 Dataset Overview

The dataset `Sleep_health_and_lifestyle_dataset.csv` includes 374 records with attributes related to:

- **Demographics**: Age, Gender, Occupation
- **Health Metrics**: BMI Category, Sleep Duration, Quality of Sleep, Physical Activity
- **Lifestyle Factors**: Daily Steps, Caffeine Intake, Alcohol Consumption, Smoking Status
- **Stress Indicators**: Stress Level (1–10), Heart Rate, Blood Pressure

**Target variables for prediction:**
- Sleep disorder
- Sleep quality classification

---

## 🔍 Objectives

- Analyze how stress and lifestyle factors affect sleep.
- Visualize correlations between health, stress, and sleep quality.
- Predict sleep disorders or poor sleep quality using classification models.

---

## 🛠️ Techniques Used

### Data Preprocessing
- Handling missing values
- Label encoding and one-hot encoding
- Normalization and outlier removal

### Data Visualization
- Correlation heatmaps
- Histograms & boxplots
- Pairplots and bar graphs

### Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine

### Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision / Recall / F1-score
- ROC-AUC Score

---

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/stress-sleep-health-analysis.git
pip install -r requirements.txt
jupyter notebook stress-affection-on-sleep-and-health.ipynb


📈 Key Findings
Higher stress levels were strongly correlated with poor sleep quality.
Caffeine intake and late-night work patterns worsened sleep health.
Random Forest and SVM achieved high accuracy in predicting sleep disorders.

🔮 Future Scope
Integrate wearable device data (e.g., Fitbit or Apple Health).
Build a dashboard with Streamlit for real-time analysis.
Perform deep learning-based time-series modeling for sleep tracking.


cd stress-sleep-health-analysis

