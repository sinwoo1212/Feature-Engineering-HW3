# Feature Engineering Pipeline

빅데이터분석 과제 3 - Feature Engineering 파이프라인 구현 및 성능 비교

## 1. Dataset

- Titanic Dataset
- Samples: 891
- Target: Survived
- Task: Binary Classification

## 2. Implementation

- Exploratory Data Analysis (EDA)
- Missing Value Imputation
- One-Hot / Ordinal Encoding
- Standard / MinMax / Robust Scaling
- Feature Engineering (FamilySize, IsAlone)
- Feature Selection
- Logistic Regression / Random Forest
- GridSearchCV
- SHAP Analysis
- AutoML (FLAML)
- Permutation Importance

## 3. Results

The highest test accuracy among the Base and Exp-1~3 experiments was 0.8268, achieved by Random Forest in Exp-3.

The corresponding F1-score was 0.7737.

## 4. How to Run

1. Open `Feature_Engineering_HW3.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Check the preprocessing results, evaluation metrics, and visualizations.

## 5. Libraries

pandas, numpy, matplotlib, seaborn, scikit-learn, shap, flaml, lightgbm
