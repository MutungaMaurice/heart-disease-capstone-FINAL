# Heart Disease Prediction

## Project Overview
This project aims to predict the presence of heart disease using clinical features from patient data. It leverages supervised machine learning algorithms and follows a robust data science workflow, including data preprocessing, exploratory analysis, feature engineering, model selection, and evaluation.

## Problem Statement
Heart disease is the leading cause of death globally. Early detection is crucial for preventive healthcare, cost reduction, and improved patient outcomes. The goal is to build a binary classification model to assist clinicians in identifying at-risk patients.

## Dataset
- **Source:** Kaggle (redwankarimsony/heart-disease-data)
- **Records:** 920 patients
- **Features:** 14 clinical features
- **Target:** Presence of heart disease (binary)

## Workflow
1. **Data Loading:** Multi-source loading with fallback (env, local, Kaggle)
2. **Preprocessing:** Imputation, scaling, encoding
3. **EDA:** Distribution, correlation, relationships
4. **Feature Engineering:** Selection and creation
5. **Modeling:** Logistic Regression, Random Forest, SVM, MLP
6. **Evaluation:** 5-fold cross-validation, metrics (F1, Accuracy, Precision, Recall, ROC AUC)
7. **Reporting:** Visualizations, classification reports, model persistence

## Results
All tested models achieved perfect scores (F1, Accuracy, Precision, Recall, ROC AUC = 1.0000) on this dataset. Logistic Regression was selected as the best model for deployment due to its interpretability and performance.

## Artifacts
- **Models:** Saved in `artifacts/` (e.g., best_model_LogisticRegression.joblib)
- **Reports:** Classification reports for each model
- **Visualizations:** Confusion matrices, ROC curves, heatmaps

## Business Impact
- Clinical decision support for early screening
- Risk assessment for patient prioritization
- Cost reduction through early detection
- Improved patient outcomes

## Limitations & Future Work
- Expand dataset for better generalization
- Engineer additional features
- Validate on external datasets
- Integrate with real-time clinical systems

## Directory Structure
```
heart_disease_capstone/
├── heart_disease_capstone_FINAL.ipynb
├── artifacts/
│   ├── best_model_LogisticRegression.joblib
│   ├── best_model_CORRECTED_SVM.joblib
│   ├── classification_report_LogisticRegression.txt
│   ├── classification_report_MLP.txt
│   ├── classification_report_RandomForest.txt
│   ├── classification_report_SVM.txt
│   └── final_project_report.md
├── figures/
├── back/
│   ├── heart_disease_capstone.ipynb
│   └── heart_disease_capstone copy.ipynb
```

## How to Run
Open `heart_disease_capstone_FINAL.ipynb` and follow the notebook cells to reproduce the analysis and model training steps.

# heart-disease-capstone-FINAL
