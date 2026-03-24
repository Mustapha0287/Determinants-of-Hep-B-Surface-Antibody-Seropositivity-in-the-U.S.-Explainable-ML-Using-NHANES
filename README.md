# Determinants-of-Hep-B-Surface-Antibody-Seropositivity-in-the-U.S.-Explainable-ML-Using-NHANES
This project applies ML and explainable artificial intelligence (XAI) methods to investigate determinants of HBsAb seropositivity using data from NHANES. The primary objective is to identify key factors associated with HBV immunity and to evaluate the predictive performance of multiple ML models in classifying seroprotection.

**Abstract**

**Background:** Hepatitis B vaccination is highly effective, yet gaps in population-level serologic immunity persist in the United States. 
Understanding the determinants of hepatitis B surface antibody (HBsAb) seropositivity is critical for guiding prevention strategies, as it indicates 
immunity to hepatitis B. This study integrates traditional epidemiologic methods with explainable machine learning to identify factors associated with 
HBsAb seropositivity using nationally representative data.

**Methods:** We conducted a cross-sectional analysis of adults participating in the National Health and Nutrition Examination Survey (NHANES) 2021-2023, 
with NHANES 2017-2018 used for external validation. Survey-weighted logistic regression was applied to estimate associations between sociodemographic, behavioral, 
and clinical factors and HBsAb seropositivity. In parallel, multiple machine learning models, including Logistic Regression, Gradient Boosting, Random Forest, 
Decision Tree, Support Vector Machine, K-Nearest Neighbors, XGBoost, and Naïve Bayes, were trained on SMOTE-balanced data and evaluated on an unresampled external test set. 
Model performance was assessed using AUROC, accuracy, precision, recall, F1-score, balanced accuracy, and PR-AUC. SHapley Additive exPlanations (SHAP) and 
Local Interpretable Model-Agnostic Explanations (LIME) were used to interpret model predictions.

**Results:** Overall, 26.7% of U.S. adults were HBsAb seropositive. In multivariable regression, older age, lower educational attainment, unmarried status, underweight, 
and obesity were associated with reduced odds of HBsAb seropositivity, while female sex, foreign-born status, and military service were associated with higher odds. 
Random Forest demonstrated the most favorable performance. SHAP analyses identified age, education, BMI, race/ethnicity, and nativity as the most influential predictors.

**Conclusions:** Integrating epidemiologic modeling with explainable machine learning provides complementary, interpretable insights into determinants of 
HBV seroprotection. These findings highlight persistent immunity gaps and support targeted public health strategies to strengthen hepatitis B prevention efforts.
