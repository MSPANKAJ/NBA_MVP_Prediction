# 🏀 ML Final Project: Regression Modeling for MVP Prediction

This project explores regression-based machine learning techniques to predict a target variable related to player performance (e.g., MVP prediction or player value estimation across multiple sports seasons).

---

## 📁 Files

- `ML_Final_Project.ipynb`: Jupyter Notebook with complete data loading, preprocessing, modeling, evaluation, and visualization.
- `models/`: Folder containing model objects (if exported)
- `data/`: CSV files containing season-wise player data

---

## 🔧 Technologies Used

- Python 3.x
- Scikit-learn
- LightGBM
- SHAP for model explainability
- Seaborn & Matplotlib for data visualization

---

## 🧪 Models Implemented

- **Linear Regression**
- **SVR (Support Vector Regressor)**
- **Elastic Net**
- **Random Forest Regressor**
- **AdaBoost Regressor**
- **Gradient Boosting Regressor**
- **LGBM Regressor**

Hyperparameter tuning is performed using `GridSearchCV`.

---

## 📊 Evaluation Metrics

- `R² Score`
- `Mean Squared Error (MSE)`

---

## 📈 Feature Importance

- SHAP values are used to understand feature contributions across models.
- Visualizations include summary plots and correlation heatmaps.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mvp-regression-project.git
   cd mvp-regression-project
