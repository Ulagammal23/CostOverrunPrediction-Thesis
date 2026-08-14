**SHAP Interpretation Notes**

**Purpose**

SHAP is applied to the selected best-performing models (CatBoost for Model A and Model B) to provide transparent global and local interpretations of predictions.

**Global Interpretation**

  - Global SHAP summary plots
  - Mean absolute SHAP value ranking table
  - SHAP dependence plots for top-ranked features

**Local Interpretation**
  
  - SHAP waterfall plots for representative projects
  - Local explanations demonstrate feature-level contributions to individual predictions

**Key Global Findings**

  - Model A: Cost_per_Day, Planned_Duration, and Planned_Cost_log are the dominant features.
  - Model B: Planned_Duration becomes the top feature; macroeconomic indicators such as     nonresidential_construction_spending appear among the top contributors.

**Interpretation Rationale**

  - Global SHAP outputs support the identification of the most influential features across the dataset.
  - Local SHAP outputs support project-level explanations for stakeholders.
  - Combined interpretations enhance transparency and decision-support usability.

**Notes**

Interpretation is discussed in detail in Chapter 5 of the dissertation.
