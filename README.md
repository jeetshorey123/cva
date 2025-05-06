# cva
Read image and convert to pixel array df
 
Xg boost Rand forest
 
 
✅ Input You Provide:
df: Your DataFrame
target_col: The name of the target column
categorical_cols: List of categorical feature column names
ordinal_cols: Dictionary of {column_name: order_list} for ordinal columns
numerical_cols: List of numerical feature column names
✅ Script Functionality:
EDA (Visual + Text fallback):
Missing value % per column
Cardinality (for categoricals)
Distribution plots (histograms, boxplots, bar charts)
Correlation heatmap for numericals
Preprocessing:
Categorical → OneHotEncoder
Ordinal → OrdinalEncoder (with your order)
Numerical → Imputer + StandardScaler
feature engineering
Train/Test Split:
Using StratifiedShuffleSplit to preserve class balance
Modeling:
Baseline with RandomForestClassifier or LogisticRegression
ensemble
Accuracy, F1 Score, Confusion Matrix
✅ Output:
Cleaned train/test sets: X_train, X_test, y_train, y_test
Trained baseline model
Metrics report
Optionally, preprocessor pipeline 
 
Categorical and ordinal and Konsa and df.info and df.describe
 
 
