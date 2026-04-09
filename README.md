# 🏠 House Price Prediction – Model Comparison & Optimization

## 📌 Project Overview

This repository contains a machine learning notebook that compares multiple regression models for predicting California house prices.

The workflow includes:

* Loading the California Housing dataset from `sklearn`
* Preprocessing and feature scaling
* Training and evaluating multiple regression models
* Comparing performance with RMSE and R² score
* Visualizing model predictions

---

## 🚀 What’s Included

* `enhanced_house_price_prediction_system.ipynb` — main notebook with the full analysis
* `requirements.txt` — Python dependencies for running the notebook

---

## 🧠 Models Compared

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

---

## 📈 Evaluation Metrics

* RMSE (Root Mean Squared Error)
* R² Score

---

## 📊 Notebook Highlights

* Data loading and inspection
* Standard scaling of features
* Train/test split
* Model training and prediction
* Model comparison table
* Individual and combined Actual vs Predicted plots
* Best model selection and justification

---

## 🛠️ Technologies Used

* Python
* pandas
* numpy
* matplotlib
* scikit-learn

---

## ✅ How to Run

1. Clone the repo:

```bash
git clone https://github.com/Prashant517/House-Price-Prediction-Model-Comparison-and-Optimization.git

cd House-Price-Prediction-Model-Comparison-and-Optimization
```

2. (Recommended) Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install requirements:

```bash
pip install -r requirements.txt
```

4. Open and run the notebook:

```bash
jupyter notebook enhanced_house_price_prediction_system.ipynb
```

---

## 📌 Notes

* The project is notebook-based, so the main work is in `enhanced_house_price_prediction_system.ipynb`.
* `seaborn` is not required for the current notebook implementation.
* If you want a cleaner repository, consider excluding the `venv/` folder from version control.

---

## 🔧 Suggested Improvements

* Add hyperparameter tuning with `GridSearchCV` or `RandomizedSearchCV`
* Include cross-validation for more robust model comparison
* Add more tree-based models such as Random Forest or Gradient Boosting
* Save the best model using `joblib` or `pickle`

---

## 👤 Author

Prashant Kulmitra
