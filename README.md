# credit-risk


This project compares the performance of **XGBoost** and **Random Forest** in predicting credit risk using the **German Credit Data**.

# Objective
Evaluate and compare two ensemble models for creditworthiness prediction.

# Evaluation Metrics
- F1-Score (10-fold Cross Validation)
- ROC AUC
- SHAP values
- Wilcoxon Signed-Rank Test

# Key Results
- **XGBoost Mean F1**: 0.831
- **Random Forest Mean F1**: 0.845
- **Wilcoxon Test p-value**: 0.064 → *No significant difference*

# Files
- `model_comparison.ipynb` – All code and plots
- `data/` – Preprocessed dataset
- `shap_plots/` – Explainability visualizations
- `results/` – ROC curves and F1 scores

#Setup
```bash
pip install -r requirements.txt
```

#Author
**Navid Goodarzi**  
GitHub: [Navidgoodi]  
Email: [navidgoodarzi19@gmail.com]

---
