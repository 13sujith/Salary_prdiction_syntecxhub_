# Salary Prediction using Regression Models

## 📌 Project Overview
This project predicts employee salary based on experience, test score,
interview score, and education level using regression techniques.

## 🎯 Objectives
- Build a salary prediction model using regression
- Handle categorical features using encoding
- Compare single-feature and multiple-feature models
- Evaluate models using RMSE and R² score
- Save the best-performing model

## 📂 Dataset
- Custom dataset with the following features:
  - Experience (Years)
  - Test Score
  - Interview Score
  - Education (UG / PG)
- **Target**: Salary

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## ⚙️ Models Used
- Simple Linear Regression (Experience vs Salary)
- Multiple Linear Regression (All Features)

## 📊 Evaluation Metrics
- RMSE (Root Mean Squared Error)
- R² Score (Coefficient of Determination)

## 📈 Results
- Multiple feature regression performed better than single feature regression.
- Education and experience significantly impact salary prediction.

## 💾 Model Saving
The best-performing model is saved using `joblib` for reuse.

## 🚀 How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells step by step

## 🧠 Conclusion
This project highlights how multiple features improve prediction accuracy
and demonstrates a practical regression-based salary prediction system.

