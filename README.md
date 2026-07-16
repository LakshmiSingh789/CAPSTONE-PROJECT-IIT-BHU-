# Machine Learning-Based Prediction of Mechanical Properties and Fe–C Phase Diagram Analysis

## 📌 Project Overview

This project implements a machine learning framework for predicting the mechanical properties of medium carbon steel using its chemical composition and heat treatment parameters. Three regression models—Random Forest, Artificial Neural Network (ANN), and XGBoost—are developed and compared based on prediction accuracy. The project also includes explainable AI (SHAP), feature importance analysis, residual analysis, and visualization of the Iron–Carbon (Fe–C) phase diagram.

---

## 🎯 Objectives

- Predict the mechanical properties of steel.
- Compare Random Forest, ANN, and XGBoost models.
- Identify the most influential alloying elements.
- Explain model predictions using SHAP.
- Visualize the Fe–C Phase Diagram.
- Evaluate models using standard regression metrics.

---

## 📂 Repository Structure

```
CAPSTONE-PROJECT-IIT-BHU-/
│
├── ML-for-FeC-Phase-Diagram.ipynb
├── NIMS_Fatigue.csv
├── README.md
├── requirements.txt
└── images-outputs/)
```

---

## 📊 Dataset

**File Name**

```
NIMS_Fatigue.csv
```

The dataset contains:

- Chemical composition
- Heat treatment parameters
- Mechanical properties
- Tensile Strength
- Hardness

### Input Features

- NT
- QT
- TT
- C
- Si
- Mn
- P
- S
- Ni
- Cr
- Cu
- Mo
- (and other alloying elements)

### Target Variables

- Tensile Strength
- Hardness

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- SHAP

---

## 🤖 Machine Learning Models

### 1. Random Forest Regressor

Random Forest combines multiple decision trees to improve prediction accuracy while reducing overfitting.

---

### 2. Artificial Neural Network (ANN)

The ANN learns nonlinear relationships between alloy composition and mechanical properties using multiple hidden layers.

---

### 3. XGBoost

XGBoost is a gradient boosting algorithm that builds decision trees sequentially and generally provides superior prediction performance.

---

## 📈 Performance Metrics

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Visualizations

The notebook generates:

- Correlation Heatmap
- Feature Importance
- Residual Plot
- Predicted vs Actual Plot
- SHAP Summary Plot
- Fe–C Phase Diagram
- Model Comparison Chart

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/LakshmiSingh789/CAPSTONE-PROJECT-IIT-BHU-.git
```

Move into the project folder

```bash
cd CAPSTONE-PROJECT-IIT-BHU-
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```bash
jupyter notebook ML-for-FeC-Phase-Diagram.ipynb
```

or

Upload the notebook to Google Colab and run all cells.

---

## 📋 Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
4. Exploratory Data Analysis
5. Feature Scaling
6. Train-Test Split
7. Random Forest
8. ANN
9. XGBoost
10. Cross Validation
11. Model Evaluation
12. SHAP Explainability
13. Feature Importance
14. Fe–C Phase Diagram
15. Final Prediction

---

## 📚 References

- Scikit-learn Documentation
- TensorFlow Documentation
- XGBoost Documentation
- SHAP Documentation

---

## 👩‍💻 Author

Lakshmi Singh

Department of Computer Science and Engineering

Assistant Professor (MPEC, Kanpur)

GitHub:
https://github.com/Lakshmisingh789
