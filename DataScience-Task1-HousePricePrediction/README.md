# Task 1: House Price Prediction System

## 📌 Project Overview
This project predicts residential house prices based on various features such as median income, house age, average rooms, and geographical location. To achieve optimal performance, two popular machine learning algorithms—**KNN Regressor** and **Linear Regression**—were built, evaluated, and compared within the same pipeline.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Environment:** Google Colab / Jupyter Notebook
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (`LinearRegression`, `KNeighborsRegressor`, `StandardScaler`, `train_test_split`)

## 📊 Methodology & Workflow
1. **Dataset:** Used the standard California Housing dataset.
2. **Preprocessing & Scaling:** Cleaned missing values and standardized feature ranges using `StandardScaler` to ensure optimal performance for KNN.
3. **Model Training & Comparison:**
   - Trained **K-Nearest Neighbors (KNN)** with tuned $K$-neighbors and weighted distance.
   - Trained **Linear Regression** as a baseline model.
4. **Evaluation:** Evaluated both models using $R^2$ Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/OIBSIP.git](https://github.com/YourUsername/OIBSIP.git)
