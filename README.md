# health-habit-ml-analyzer
ML-based app that predicts next-week health habit consistency
# 🧠 ML-Based Health Habit Analyzer

A machine learning web application that predicts a user’s **next-week health habit consistency score** based on recent behavioral data such as sleep, activity, water intake, and habit adherence.

---

## 🚀 Features
- Supervised ML regression model
- Predicts habit consistency on a 0–100 scale
- Clean, modern UI (Streamlit)
- AI-style human-readable summary
- End-to-end ML pipeline

---

## 🧠 Machine Learning Details
- Model: Linear Regression
- Problem Type: Regression
- Target Variable: Next-week habit consistency score
- Evaluation Metric: Mean Absolute Error (MAE)

### Input Features
- Average daily steps
- Average sleep duration
- Water intake
- Missed habit days
- Variance in steps & sleep
- Previous week consistency score

---

## 🖥️ Tech Stack
- Python
- scikit-learn
- Streamlit
- Pandas & NumPy

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
