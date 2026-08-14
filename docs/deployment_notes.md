**Current Status**

The implementation is a research prototype developed in Google Colab. No production deployment was implemented as part of this dissertation.

**Future Deployment Opportunities**

The framework can be deployed as a decision-support tool for construction stakeholders. Potential deployment strategies include:

  - Streamlit web application for interactive predictions
  - Flask or FastAPI service for backend integration
  - Cloud-based dashboards (Azure ML, AWS SageMaker, GCP AI Platform)
  - Integration with construction project management platforms

**Expected Deployment Inputs**

  - Project type
  - Location
  - Planned cost
  - Planned duration
  - Start date (for FRED alignment)

**Expected Deployment Outputs**

  - Predicted probability of cost overrun
  - Risk category (Low, Medium, High)
  - SHAP-based explanation for the prediction

**Considerations for Future Work**

  - Secure data handling and access control
  - Real-time inference performance
  - Integration with organisational databases
  - User interface design and stakeholder usability
  - Continuous monitoring and periodic model updates
