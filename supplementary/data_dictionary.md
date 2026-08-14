**Data Dictionary**

**Project-Level Features (BIM-AI Dataset)**

**Project_Type Description:** Category of construction project (Building, Bridge, Road, Dam, Tunnel) Type: Categorical

**Location Description:** Geographic location of the project (Chicago, Houston, Los Angeles, New York, Seattle) Type: Categorical

**Planned_Cost Description:** Initial project cost estimate in USD Type: Numerical

**Planned_Duration Description:** Planned project duration in days Type: Numerical

**Cost_per_Day Description:** Planned_Cost divided by Planned_Duration Type: Derived numerical feature

**Planned_Cost_log Description:** Log-transformed Planned_Cost Type: Derived numerical feature

**Duration_Category Description:** Discretised categorical grouping of Planned_Duration Type: Categorical

**Cost_Overrun_Percent Description**: Percentage overrun of actual cost above planned cost Type: Continuous target

**Cost_Overrun_Binary Description**: Binary target variable (1 = overrun, 0 = no overrun) Type: Categorical target

**External Macroeconomic Features (FRED Indicators)**

**total_construction_spending Description:** Total US construction spending (TTLCONS) Type: Numerical

**residential_construction_spending Description:** Total residential construction spending (TLRESCONS) Type: Numerical

**nonresidential_construction_spending Description:** Total non-residential construction spending (TLNRESCONS) Type: Numerical

**construction_pct_change Description:** Monthly percentage change in construction spending Type: Numerical

**Notes**

All dataset variables are aligned to the project start month for temporal consistency.
