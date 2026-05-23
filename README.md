## Predictive Churn Modeling Pipeline
### 📝 Project Overview
RetainPulse is a predictive engine designed to identify high-risk customer churn within the Telco sector. Moving beyond simple heuristics, this project implements a Random Forest architecture optimized for high-precision classification on the IBM Telco Dataset.

### 🛠️ The Engineering Pipeline
The project follows a rigorous pre-production workflow to ensure model stability and feature integrity:

**Automated Preprocessing**: Custom pipeline for handling missing values, One-Hot Encoding for multi-class features, and Label Encoding for binary targets.

**Feature Scaling**: Applied StandardScaler to ensure uniform distribution across numerical features like Tenure and MonthlyCharges.

**Optimization**: Leveraged GridSearchCV for exhaustive hyperparameter tuning (n_estimators, max_depth, min_samples_split).

**Robustness Testing**: Implemented Stratified K-Fold Cross-Validation to validate model generalization across unseen data segments.

### 📊 Performance Metrics
The model was validated using a 10-fold cross-validation strategy, ensuring that accuracy is not just high, but stable.

### Results
Mean Accuracy: ~80%

Standard Deviation: 1.34%
