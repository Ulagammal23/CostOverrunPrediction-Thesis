**Methodology Notes**

**Objective**

Develop a transparent, interpretable machine learning framework for early-stage prediction of construction cost overruns, integrating pre-construction project characteristics with monthly macroeconomic indicators.

**Datasets**

- BIM-AI 1000 Construction Projects Dataset (project-level characteristics)
- Federal Reserve Economic Data (FRED)
      - Total Construction Spending (TTLCONS)
      - Total Residential Construction Spending (TLRESCONS)
      - Total Non-Residential Construction Spending (TLNRESCONS)
      - Construction Sector Monthly Percent Change

**Workflow**

  1. Data Collection and Integration
  2. Data Preprocessing
  3. Data Transformation
  4. Feature Engineering
  5. Model Development
  6. Hyperparameter Tuning
  7. Validation-Based Model Selection
  8. Final Test Evaluation
  9. SHAP Interpretation
  10. Risk Category Validation

**Ablation Design**

  - Model A: Tier 1 features + Duration_Category
  - Model B: Tier 1 + Tier 2 macroeconomic indicators + Duration_Category

**Machine Learning Algorithms**
 
  - Logistic Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - CatBoost

**Model Selection**

Selection is based exclusively on tuned validation AUC-ROC. Test data is used only for final evaluation.

**Selected Model**

CatBoost is selected for both Model A and Model B based on validation performance.

**Interpretability**

  - Global SHAP feature ranking and summary plots
  - SHAP dependence plots
  - SHAP local explanations for representative projects

**Notes**

This document summarises the workflow at a high level. Full methodological detail is provided in Chapters 3 and 4 of the dissertatio
