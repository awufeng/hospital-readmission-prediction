# hospital-readmission-prediction
Hospital readmissions can significantly impact healthcare costs and patient outcomes. This project builds and interprets machine learning models to predict the likelihood of patient readmission based on demographic, clinical, and admission data.

The repository includes data preprocessing, feature engineering, model training, and explainability analysis (e.g., SHAP values and feature importance).

Objectives

- Preprocess and clean hospital admission records.
- Train and evaluate machine learning models for predicting readmissions.
- Identify the most influential features contributing to predictions.
- Use SHAP values for model explainability and to support clinical decision-making.

Key Findings

- Analysis of feature importances from the XGBoost model revealed that prior hospital utilization, particularly the number of previous inpatient admissions and emergency visits, was the strongest predictor of readmission. 
- Discharge disposition also played a critical role: patients discharged home, transferred to another facility, or sent to hospice care showed distinct risk profiles. 
- Chronic conditions such as diabetes (presence or absence of medication), circulatory disorders, musculoskeletal issues, and neoplasm were consistently associated with higher readmission likelihood. 
- These findings highlight the importance of proactive discharge planning, chronic disease management, and targeted follow-up for high-risk patient groups to reduce avoidable readmissions.
