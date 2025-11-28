# XAI Analysis Notebook — README

## Notebook: `XAI.ipynb`

This notebook contains the full workflow for Explainable AI (XAI) analysis on psychological constructs using SHAP, LIME, and model-specific interpretation techniques. It supports interpretability and results sections of the SXGA research project.

### Contents
- Data preparation
- Model training (SVM, XGBoost, hybrid architecture)
- SHAP global and local explanations
- LIME explanations
- Feature importance analysis

### How to Run
```
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate    # Windows
pip install -r requirements.txt
jupyter notebook
```

### Dependencies
```
numpy
pandas
scikit-learn
shap
lime
matplotlib
seaborn
xgboost
ipykernel
```
