# NJeanine-creator-JeanineNISHIMWE-ML-Assignment
AI Learning Assignment
# Titanic Survival Prediction - ML Assignment

This project is part of the AI (ML) & Big Data course under instructor Victor Muv. The objective is to complete a full data science pipeline: Data Cleaning → EDA → ML → UI.

## 📁 Dataset
Used the Titanic dataset (`train.csv`) for survival prediction.

## 🚀 Project Pipeline

### 1. Data Cleaning
- Loaded data using Pandas.
- Filled missing `Age` values with the mean.
- Dropped missing values in `Embarked`.
- Removed duplicate rows.

### 2. Exploratory Data Analysis (EDA)
- Summary statistics with `df.describe()`.
- Visualizations using Seaborn & Matplotlib:
  - Age distribution histogram
  - Survival rate by gender
  - Correlation heatmap

### 3. Machine Learning
- Used `RandomForestClassifier` from scikit-learn.
- Split data using `train_test_split`.
- Evaluated using accuracy and classification report.

### 4. UI
- Built using Streamlit.
- Takes inputs like Age, Pclass, and SibSp.
- Outputs survival prediction.