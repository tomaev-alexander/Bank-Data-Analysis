# Bank-Data-Analysis
In this project I use ML tools to solve a binary classification problem on synthetic banking data

This is a solo project

## 📦 Libraries Used

| Category | Library | Purpose |
|----------|---------|---------|
| **Data Processing** | `pandas` | Data manipulation and analysis |
| | `numpy` | Numerical computations |
| | `sklearn.preprocessing.LabelEncoder` | Encode categorical labels to numbers |
| | `sklearn.preprocessing.StandardScaler` | Feature standardization / normalization |
| **Visualization** | `matplotlib.pyplot` | Plotting and graphs |
| | `seaborn` | Statistical data visualization |
| **Data Splitting & Validation** | `sklearn.model_selection.train_test_split` | Split data into train/test sets |
| | `sklearn.model_selection.KFold` | Standard cross-validation |
| | `sklearn.model_selection.StratifiedKFold` | Stratified cross-validation (preserves class balance) |
| **Hyperparameter Tuning** | `sklearn.model_selection.GridSearchCV` | Exhaustive grid search for best hyperparameters |
| | `optuna` | Bayesian hyperparameter optimization |
| **Machine Learning (General)** | `scikit-learn` | ML algorithms and utilities |
| **Evaluation Metrics** | `sklearn.metrics.average_precision_score` | Average precision (PR-AUC) |
| | `sklearn.metrics.precision_score` | Precision metric |
| | `sklearn.metrics.recall_score` | Recall metric |
| | `sklearn.metrics.f1_score` | F1-score metric |
| **Imbalanced Learning** | `imblearn.over_sampling.SMOTE` | Synthetic Minority Over-sampling for imbalanced classes |
| **Gradient Boosting (ML)** | `lightgbm` | LightGBM algorithm |
| | `xgboost` | XGBoost algorithm |
| | `catboost` | CatBoost algorithm |
