# Crop-Yield-Prediction-at-District-Level-in-India
Machine learning-based crop yield prediction at district level in India using XGBoost, Random Forest, and MLP with explainable AI (SHAP).

## 📌 Overview

This project focuses on predicting crop yield at the district level in India using machine learning techniques. The goal is to build an accurate and interpretable model that can assist in agricultural planning and decision-making.

The project uses real-world agricultural data and compares multiple models to identify the most effective approach for yield prediction.

---

## 🚀 Key Features

* District-level crop yield prediction
* Comparison of multiple ML models (Random Forest, XGBoost, MLP)
* Temporal validation (train on past, test on future)
* Explainable AI using SHAP
* Error analysis across districts

---

## 📊 Dataset

* Source: Kaggle – Crop Production in India
* Features:

  * State, District, Crop, Season, Area, Production
* Target:

  * Yield = Production / Area

---

## ⚙️ Methodology

1. Data Cleaning & Preprocessing
2. Feature Engineering (One-hot encoding)
3. Temporal Train-Test Split
4. Model Training:

   * Random Forest
   * XGBoost
   * MLP
5. Evaluation using RMSE, MAE, R²
6. Explainability using SHAP
7. Error Analysis (district-level)

---

## 🧠 Models Used

* Random Forest
* XGBoost (Best Performing Model)
* Multi-Layer Perceptron (MLP)

---

## 📈 Results

* XGBoost achieved the best performance
* Tree-based models outperformed neural networks
* Key influencing factors:

  * Crop type
  * Cultivated area
  * Season

---

## 🔍 Key Insights

* District-level prediction improves precision
* High error regions indicate need for additional features (weather, soil)
* Explainability helps in understanding model behavior

---

## 📂 Project Structure

Crop-Yield-Prediction-India/
│
├── data/
│   ├── raw/                
│   ├── processed/    
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── Model_Training.ipynb 
│
├── src/
│   ├── preprocessing.py
│   ├── train_model.py
│   ├── evaluate.py
│
├── results/
│   ├── figures/
│   │   ├── fig1_architecture.png
│   │   ├── fig2_preprocessing.png
│   │   ├── fig3_model_workflow.png
│   │   ├── fig4_actual_vs_pred.png
│   │   ├── fig5_confusion_matrix.png
│   │   ├── fig6_shap.png
│   │   ├── fig7_error_analysis.png
│   │
│   ├── metrics.csv
│
├── paper/
│   ├── final_paper.pdf
│
├── requirements.txt
├── README.md
└── .gitignore

---

## 📸 Sample Outputs

* Actual vs Predicted Graph
* Confusion Matrix
* SHAP Feature Importance
* Error Analysis by District

---

## 📄 Research Paper

📌 This project is based on our accepted research paper:
**"Crop Yield Prediction at District Level in India Using Machine Learning"**

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* SHAP

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

---


## ⭐ Future Improvements

* Add weather & soil data
* Deploy as web app
* Real-time prediction system

---
