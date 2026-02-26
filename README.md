# Feature Engineering for Predictive Modeling | House Prices Dataset

## Project Overview
This project focuses on designing and executing a strategic feature engineering pipeline for the Kaggle House Prices dataset.

The objective was not to build a predictive model, but to transform the raw dataset into a structured and machine-learning-ready format through thoughtful cleaning, transformation, encoding, and dimensionality reduction.

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Scikit-learn
- PCA for dimensionality reduction

## Key Steps Performed

### 1️⃣ Data Cleaning
- Handled missing values based on feature meaning
- Treated outliers using IQR method
- Differentiated between “missing” and “not applicable”

### 2️⃣ Numeric Feature Engineering
- Log transformation of skewed variables
- Created new composite features (e.g., TotalBathrooms, TotalSF)
- Applied scaling for PCA compatibility

### 3️⃣ Categorical Encoding
- Ordinal encoding for ordered categories
- One-hot encoding for nominal variables

### 4️⃣ Text Feature Representation
- Combined descriptive text columns
- Applied basic vectorization

### 5️⃣ Dimensionality Reduction
- Applied PCA to reduce redundancy
- Evaluated explained variance
- Assessed loading of random student feature

## Special Requirement
A unique random feature was generated based on my student ID and treated as a regular numeric feature throughout analysis.

## Key Insights
- Several numeric features were highly skewed and required log transformation.
- Strong multicollinearity existed among area-related variables.
- The student-generated random feature showed minimal meaningful correlation, confirming its artificial nature.

## Files Included
- house_prices_feature_engineering.ipynb (Fully executed notebook)
- house_prices_raw_dataset.csv
- feature_engineering_report.pdf
