# 🌡️ Heat Code - Chennai Weather Prediction

This repository contains my solution for the **Heat Code by FODSE** machine learning challenge.  
The task was to **predict Chennai’s temperature for Sunday (10 AM – 9 PM)** using historical weather data.

---

## 📌 Problem Statement
- Predict 12 hourly temperature values (10:00–21:00) for Sunday.  
- Output format: `submission.csv` with two columns (`ID`, `temperature_prediction`).  
- Evaluation metrics: **MAE**, **RMSE**, and **R² score**.

---

## 🛠️ Approach
- Exploratory analysis of weather dataset.  
- Feature engineering (time-based features, lagged temperatures, etc.).  
- Trained models: **XGBoost**, **LightGBM**, and ensembling.  
- Final submission created by combining predictions.  

---

## 📂 Files
- `notebook.ipynb` → Kaggle notebook with full workflow.  
- `submission.csv` → Final predictions (12 rows).  
- `README.md` → Project description.  

---

## 📊 Results
- Achieved leaderboard score: **2.6969 (MAE-RMSE-R² blend)**.  
- **Ranked #10** on the public leaderboard (first attempt 🚀).  

---

## 🚀 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/chennai-weather-prediction.git
   cd chennai-weather-prediction
