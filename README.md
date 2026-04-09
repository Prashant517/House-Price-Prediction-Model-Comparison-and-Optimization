# 🏠 House Price Prediction – Model Comparison & Optimization

## 📌 Project Overview

This project demonstrates a complete machine learning workflow to predict California house prices and compare multiple regression models.

The goal is to move beyond a single model approach and adopt a **data-driven model selection strategy** based on performance metrics.

---

## 🚀 Key Highlights

* 📊 End-to-end ML pipeline (data → model → evaluation → visualization)
* ⚖️ Feature scaling using StandardScaler
* 🤖 Multiple regression models compared
* 📈 Evaluation using RMSE & R² Score
* 📉 Visual comparison of predictions
* 🏆 Automatic best model selection
* 📌 Model justification (real-world ML practice)

---

## 🧠 Models Used

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

---

## 📊 Model Performance

| Model             | RMSE ↓    | R² Score ↑ |
| ----------------- | --------- | ---------- |
| Linear Regression | ~0.74     | ~0.57      |
| Ridge Regression  | ~0.74     | ~0.57      |
| Decision Tree     | **~0.70** | **~0.62**  |

---

## 🏆 Best Model

**Decision Tree Regressor**

### 📌 Justification

The Decision Tree model achieved:

* Highest R² Score
* Lowest RMSE

It performs better because it can capture **non-linear relationships** in the dataset, unlike linear models.

---

## ⚠️ Important Insight

Although Decision Tree performed best, it may lead to **overfitting** if not controlled.

👉 In production, hyperparameters like `max_depth` should be tuned using cross-validation.

---

## 🧠 Dataset

* 📂 California Housing Dataset (from sklearn)
* 🎯 Target Variable: `MedHouseVal`

### Features include:

* Median Income
* House Age
* Average Rooms
* Population
* Location-based features

---

## 🛠️ Technologies Used

* Python
* pandas
* numpy
* matplotlib
* scikit-learn

---

## 📁 Project Structure

```
├── enhanced_house_price_prediction_system.ipynb
├── requirements.txt
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Prashant517/House-Price-Prediction-Model-Comparison-and-Optimization.git
cd House-Price-Prediction-Model-Comparison-and-Optimization
```

### 2. Create virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook enhanced_house_price_prediction_system.ipynb
```

---

## 📈 Visualizations

* Actual vs Predicted plots (for each model)
* Combined model comparison graph
* Best model performance visualization

---

## 🔥 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Random Forest implementation
* Feature importance visualization
* Model deployment (Flask / FastAPI)

---

## 👤 Author

**Prashant Kumar Kulmitra**

---

## ⭐ Acknowledgment

This project is part of an AI/ML learning task focused on real-world model comparison and optimization.

---

## 📬 Contact

Open to opportunities in **AI / Machine Learning / Backend Development** 🚀
