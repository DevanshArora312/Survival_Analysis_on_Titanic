# Survival Analysis on Titanic Dataset using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-lightgrey)

A machine learning project analyzing survival patterns in the Titanic dataset using decision trees and feature engineering techniques.

## 📌 Overview
This project aims to predict passenger survival on the Titanic using machine learning. Through comprehensive data analysis and feature engineering, we achieve **86% accuracy** using a Decision Tree Classifier.

## 🗂 Dataset
- **Titanic Dataset**: Contains passenger information like age, gender, ticket class, fare, and survival status
- Source: Publicly available Titanic survival dataset
- Features: 12 variables including numerical and categorical data

## 🔍 Methodology
### 1. Exploratory Data Analysis (EDA)
- Visualized data distributions using Seaborn/Matplotlib
- Analyzed relationships between features and survival
- Identified missing values and data imbalances

### 2. Feature Engineering
- **Feature Extraction**: Created new features from existing data
- **Transformation**: Handled categorical variables using one-hot encoding
- **Scaling**: Normalized numerical features using StandardScaler

### 3. Machine Learning
- Implemented `DecisionTreeClassifier` from Scikit-learn
- Optimized hyperparameters through cross-validation
- Achieved **86% accuracy** on test data

## 🛠 Installation
1. Clone repository:
```
git clone https://github.com/your-username/titanic-survival-analysis.git
```
2. Create conda environment:

```
conda create -n titanic-env python=3.8
conda activate titanic-env
```

3. Install requirements:
```
pip install -r requirements.txt
```

## 📊 Results
| Metric        | Score |
|---------------|-------|
| Accuracy      | 86%   |
| Precision     | 83%   |
| Recall        | 79%   |


## 💻 Technologies
- **Python** (3.8+)
- **Scikit-learn**: For implementing the Decision Tree Classifier and other ML utilities
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Seaborn/Matplotlib**: Data visualization and EDA