# 🌱 Crop Recommendation System using Machine Learning

## 📌 Project Overview

This project is a complete end-to-end Machine Learning system designed to recommend the most suitable crop based on soil and environmental conditions.

The system analyzes soil nutrients and climatic factors to predict the best crop using a trained Random Forest model.

---

## 🎯 Objective

To build a machine learning model that:

- Predicts the most suitable crop for a given soil condition
- Uses engineered agricultural features
- Provides prediction confidence
- Returns ranked crop recommendations

---

## 📊 Dataset

The dataset includes soil and environmental variables:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall
- Crop Label

Additionally, engineered features were created:

- Total_NPK
- N_P_ratio
- N_K_ratio
- P_K_ratio

---

## 🧠 Methodology

The project follows a complete data science pipeline:

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Train-test split
5. Model training using Random Forest
6. Model evaluation
7. Prediction system development

---

## 🤖 Machine Learning Model

The final model used:

- Random Forest Classifier

### Why Random Forest?

- Handles non-linear relationships
- Robust to noise and outliers
- Works well with tabular data
- Provides feature importance

---

## 📈 Model Performance

- Accuracy: ~99%

The model shows strong predictive performance across multiple crop classes.

---

## ⚙️ System Features

The system includes:

### ✔ Automatic Feature Engineering
Derives agricultural ratios from raw inputs.

### ✔ Crop Prediction
Predicts the most suitable crop based on soil conditions.

### ✔ Confidence Score
Indicates how confident the model is in its prediction.

### ✔ Top 3 Recommendations
Returns ranked crop probabilities for better interpretability.

---

## 🧪 Example Input

```python id="readme2"
N = 90
P = 42
K = 43
temperature = 22
humidity = 82
ph = 6.5
rainfall = 120
