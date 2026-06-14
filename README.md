# HealthAssist-AI# HealthAssist AI - Early Diabetes Risk Predictor

An AI-powered Predictive Machine Learning pipeline developed for the **INDIA.RUNS 2026 National Innovation Challenge** under the **Data & AI Challenge** track.

## 👤 Participant Details
* **Name:** Krishna Jaiswal
* **Track:** Data & AI Challenge
* **Project Status:** MVP (Minimum Viable Product) Developed & Optimized

---

## 📌 Problem Statement
Early detection of chronic lifestyle diseases like diabetes is crucial for timely intervention. However, a vast population lacks immediate and affordable access to diagnostic laboratories. This project aims to bridge that gap by providing a fast, web-accessible, and data-driven screening tool using basic non-invasive physiological metrics.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Environment:** Google Colab / Jupyter Notebook
* **Machine Learning Framework:** Scikit-Learn
* **Data Manipulation:** Pandas, NumPy

---

## 📈 Technical Workflow & Optimization

1. **Dataset Generation:** Simulated a clean, realistic healthcare dataset consisting of critical physiological factors (Glucose, BMI, Insulin, Age, Blood Pressure, etc.).
2. **Data Preprocessing:** Implemented feature scaling using `StandardScaler` to normalize features with vastly different numeric ranges, ensuring unbiased model training.
3. **Model Training:** Utilized the **Random Forest Classifier** ensemble algorithm to understand intricate patterns between medical metrics and diabetes risk.
4. **Hyperparameter Tuning:** Tuned parameters like `n_estimators` (increased to 150) and restricted tree depth to optimize generalization and prevent overfitting.

### 📊 Results & Performance
* **Baseline Model Accuracy:** 61.00%
* **Optimized Model Accuracy:** **65.00%** (Achieved via precise feature engineering and parameter tuning)

---

## 🚀 How to Run the Code Locally

1. Open the notebook in **Google Colab**.
2. Run the first cell to initialize the dataset.
3. Run the second and third cells to train and optimize the AI model.
4. Use the interactive function at the bottom to test custom health profiles:

```python
predict_diabetes_risk(
    pregnancies=2, 
    glucose=140, 
    bp=80, 
    skin=25, 
    insulin=85, 
    bmi=30.0, 
    pedigree=0.5, 
    age=35
)
```

---
*Developed with ❤️ by Krishna Jaiswal for INDIA.RUNS 2026.*
