# 🏠 House Price Prediction - Task 3

## 📌 Project Overview

This project is part of my **Artificial Intelligence & Machine Learning Internship (Task 3)**. The objective is to improve the performance of machine learning models through **Model Validation**, **Overfitting Analysis**, and **Hyperparameter Tuning** using the California Housing dataset.

---

## 🎯 Objectives

- Build and evaluate multiple regression models.
- Detect overfitting by comparing training and testing performance.
- Apply 5-Fold Cross Validation.
- Perform Hyperparameter Tuning using GridSearchCV.
- Compare model performance using RMSE and R² Score.
- Select the best-performing model.

---

## 📂 Dataset

**Dataset:** California Housing Dataset

Features include:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

**Target Variable:**
- Median House Value

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🤖 Machine Learning Models

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- Tuned Decision Tree
- Tuned Random Forest

---

## 📊 Model Validation

The project uses:

- Train-Test Split
- 5-Fold Cross Validation
- RMSE
- R² Score

These evaluation methods help measure model accuracy and generalization performance.

---

## ⚙ Hyperparameter Tuning

GridSearchCV was used to optimize the following models:

### Decision Tree

- max_depth
- min_samples_split
- min_samples_leaf

### Random Forest

- n_estimators
- max_depth
- min_samples_split
- min_samples_leaf

This process improved the model's predictive performance and reduced overfitting.

---

## 📈 Model Comparison

The models were compared using:

- Training RMSE
- Testing RMSE
- Cross Validation RMSE
- R² Score

The Tuned Random Forest achieved the best overall performance.

---

## 🧠 Overfitting Analysis

Overfitting was analyzed by comparing training and testing performance.

- Decision Tree showed signs of overfitting.
- Hyperparameter tuning reduced overfitting.
- Random Forest provided better generalization.
- Tuned Random Forest delivered the most balanced performance.

---

## 🏆 Final Model

**Best Model:** Tuned Random Forest Regressor

Reasons:
- Highest prediction accuracy
- Better generalization
- Stable Cross Validation performance
- Reduced overfitting
- Improved R² Score

---

## 📁 Project Structure

```
House-Price-Prediction-Task3/
│
├── AI_ML_Task3_Model_Validation_Tuning.ipynb
├── Task3_Report.pdf
├── best_house_price_model.pkl
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository

```
git clone https://github.com/your-username/House-Price-Prediction-Task3.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the notebook

```
jupyter notebook
```

4. Run all cells.

---

## 📌 Results

- Successfully evaluated multiple regression models.
- Performed 5-Fold Cross Validation.
- Applied GridSearchCV for hyperparameter optimization.
- Reduced overfitting.
- Selected the Tuned Random Forest as the final model.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Model Validation
- Cross Validation
- Overfitting Detection
- Hyperparameter Tuning
- GridSearchCV
- Regression Evaluation
- Model Selection
- Machine Learning Best Practices

---

## 👨‍💻 Author

**Naveen Dixit**

B.Tech (Computer Science & Engineering - AI & DS)

Artificial Intelligence & Machine Learning Intern

---
