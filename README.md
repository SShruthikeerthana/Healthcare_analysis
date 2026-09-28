# Healthcare_analysis
                    diabetes.csv
                         ↓
                  Data Exploration
                         ↓
                   Data Cleaning
              (median imputation)
                         ↓
                       EDA
                         ↓
                Feature / Target Split
                         ↓
                  Train-Test Split
                         ↓
                  StandardScaler
                         ↓
                Logistic Regression
                         ↓
             ┌───────────┴───────────┐
             ↓                       ↓
       Model Evaluation        5-Fold CV
             ↓                       ↓
 Accuracy / Precision          Pipeline
 Recall / F1 / CM              prevents leakage
             ↓
      Feature Importance
             ↓
       New Patient Input
             ↓
       Probability Score
             ↓
       Risk Classification
       ┌─────┼─────┐
       ↓     ↓     ↓
      Low  Moderate High
             ↓
      Recommendation
             ↓
      Rule-based comparison
