 <b>Bank Telemarketing Campaign - Kaggle Competition <\b>
Project Overview
This project involves predicting the success of a bank's telemarketing campaign based on customer data. Leveraging data preprocessing techniques, feature engineering, and advanced machine learning models, the project achieved competitive performance in a Kaggle competition.

Key Features
Data Preparation:

Performed exploratory data analysis (EDA) to understand data patterns and identify key features.
Removed outliers, applied label encoding, and standardized numerical features.
Managed class imbalance using downsampling and Synthetic Minority Oversampling Technique (SMOTE).
Modeling and Optimization:

Trained and hypertuned Random Forest, SVM, XGBoost, and HistGradient models.
Combined predictions using a voting classifier to improve overall performance.
Used F1 Macro score as the primary evaluation metric to handle class imbalance.
Results:

Validation Set: F1 Macro Score: 0.76, ROC: 0.98.
Test Set: F1 Macro Score: 0.755.
Achieved the highest competition score of 0.78.
Workflow
Data Preprocessing:

Cleaned and transformed raw data for analysis and modeling.
Handled missing values and imbalanced classes effectively.
Feature Engineering:

Encoded categorical variables.
Standardized numerical features for model compatibility.
Model Training:

Evaluated multiple classifiers to determine the best-performing models.
Conducted hyperparameter tuning to optimize model performance.
Ensemble Learning:

Integrated model predictions using a voting classifier to enhance accuracy and robustness.
