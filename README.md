# SubSight

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-Backend-black.svg)
![React](https://img.shields.io/badge/React-Frontend-61DBFB.svg)
![Machine Learning](https://img.shields.io/badge/ML-Regression-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## Overview

**SubSight** is a full-stack machine learning application that predicts YouTube channel subscriber growth using structured channel-level features.

It combines **regression modeling, feature engineering, and a web-based interface** to deliver real-time subscriber growth predictions.

---

## Objective

To build a predictive analytics system that estimates YouTube subscriber growth and evaluates model performance using rigorous statistical and error analysis techniques.

---

## System Architecture
User Inputs (Channel Features)
↓
React Frontend (UI Layer)
↓
Flask Backend (API Layer)
↓
Machine Learning Regression Model
↓
Predicted Subscriber Growth


---

## Tech Stack

### Machine Learning
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

### Backend
- Flask (REST API)
- Postman (API testing)

### Frontend
- React.js
- HTML/CSS

---

## 🔬 Methodology

### 1. Data Collection
- Structured dataset sourced from Kaggle
- YouTube channel-level features

### 2. Feature Engineering
- Data cleaning and preprocessing
- Feature selection to reduce variance and noise

### 3. Model Development
- Regression-based machine learning model
- Trained on historical channel growth data

### 4. Evaluation
- K-fold cross-validation
- Residual and error distribution analysis

---

## Performance

- **Mean Absolute Error (MAE):** `92 subscribers`
- Stable generalization across validation folds
- Consistent residual distribution indicating reliable predictions

---

## Model Insights

- Feature engineering improved model stability and accuracy  
- Cross-validation confirmed strong generalization performance  
- Model performs best on channels with consistent engagement patterns  

---

## Features

- Predict YouTube subscriber growth in real time  
- Interactive React-based UI  
- Flask API integration for model inference  
- Transparent model evaluation metrics  

---

##  Future Improvements

- Integrate time-series forecasting (LSTM / ARIMA)
- Use real YouTube API data for live predictions
- Add engagement metrics (likes, watch time, CTR)
- Deploy to cloud (AWS / Render / Vercel)

---

## Project Structure
SubSight/
│
├── backend/ # Flask API + ML model
├── frontend/ # React UI
├── notebooks/ # Data analysis + training
├── models/ # Trained regression model
├── data/ # Dataset
├── requirements.txt
└── README.md


---

##  Key Takeaway

**SubSight** demonstrates an end-to-end machine learning pipeline combining predictive analytics with full-stack deployment, transforming raw YouTube channel data into actionable subscriber growth insights.
