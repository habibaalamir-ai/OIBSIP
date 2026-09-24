# Task 2: Customer Churn Prediction & API Deployment

## 📌 Project Overview
This project predicts customer churn using historical customer behavior data. An optimal **XGBoost Classifier** model was trained, evaluated, and encapsulated into a production-ready **FastAPI** RESTful endpoint for real-time predictions.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Data Science:** `pandas`, `numpy`, `scikit-learn`, `xgboost`
- **Visualization:** `matplotlib`, `seaborn`
- **API Framework:** `fastapi`, `uvicorn`, `pydantic`

## 📊 Methodology & Pipeline
1. **Data Preprocessing & Encoding:** Handled categorical variables using One-Hot Encoding and scaled numerical features.
2. **Model Training:** Trained an XGBoost classifier tuned for imbalanced class distributions.
3. **Evaluation Metrics:** Evaluated using Confusion Matrix, Precision, Recall, F1-Score, and ROC-AUC.
4. **Deployment:** Built a FastAPI application exposing a POST endpoint `/predict` for model inference.

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn fastapi uvicorn pydantic
