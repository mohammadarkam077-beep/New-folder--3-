# 📈 TCS Stock Price Prediction using Machine Learning & LSTM

This project focuses on predicting **Tata Consultancy Services (TCS)** stock **closing prices** using multiple machine learning models, with a primary emphasis on **Long Short-Term Memory (LSTM)** neural networks for time-series forecasting.

---

## 🚀 Project Objectives
- Perform **Exploratory Data Analysis (EDA)** on historical TCS stock data
- Apply **feature engineering** for time-series modeling
- Build and compare multiple prediction models
- Evaluate model performance using standard regression metrics

---

## 🧠 Models Implemented
- **Linear Regression (with lag features)**
- **Linear Regression (without lag features)**
- **Random Forest Regressor**
- **LSTM (Deep Learning – TensorFlow/Keras)**

---

## 🛠️ Technologies & Tools
- **Python**
- **TensorFlow / Keras**
- **Scikit-learn**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**
- **VS Code**
- **Git & GitHub**

---

## 📊 Evaluation Metrics
Models were evaluated using:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### Sample Results
| Model | RMSE (INR) | R² Score |
|------|-----------|----------|
| LSTM | ~131.9 | ~0.95 |
| Random Forest | Competitive | High |
| Linear Regression | Near-perfect (with leakage) | ~1.0 |

> ⚠️ Note: Linear Regression achieved very high accuracy due to implicit temporal information in engineered features, demonstrating the importance of handling data leakage in time-series models.

---

## 📂 Project Structure
