# 📈 Student Performance Predictor

ML model to predict student academic outcomes with explainability.

## 🔬 What it does
- **Model** — Random Forest vs. Logistic Regression with GridSearchCV → **84% accuracy, 0.81 F1**
- **Feature Engineering** — Reduced 40 → 18 features via mutual information scoring (+12% precision)
- **XAI** — SHAP explainability surfacing top-5 predictors per student segment
- **Dashboard** — Streamlit app for non-technical educators

## 📦 Stack
Python · scikit-learn · Random Forest · SHAP · Pandas · NumPy · Streamlit
