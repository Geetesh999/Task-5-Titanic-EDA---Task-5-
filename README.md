# Task 5 — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the **Titanic dataset** using Python.

The objective is to explore the dataset through statistical analysis and visualizations to identify patterns, trends, relationships, missing values, and potential outliers.

## 🎯 Objective

- Understand the structure and characteristics of the dataset
- Perform statistical exploration
- Identify missing values and potential outliers
- Analyze relationships between variables
- Visualize important patterns and trends
- Extract meaningful insights from the data

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The analysis uses the **Titanic dataset**, containing passenger information such as:

- Passenger class
- Sex
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Port of embarkation
- Survival status

The dataset contains **891 passenger records and 12 original features**.

An additional feature, `FamilySize`, was created during the analysis.

## 🔍 EDA Performed

The following analyses were performed:

### 1. Data Understanding
- `df.info()`
- `df.describe()`
- Dataset shape and data types
- Categorical value counts

### 2. Missing Value Analysis
Missing values were identified in:
- `Age`
- `Cabin`
- `Embarked`

### 3. Univariate Analysis
- Survival distribution
- Age distribution
- Fare distribution
- Boxplots for Age and Fare

### 4. Bivariate Analysis
- Survival by gender
- Survival by passenger class
- Age vs Fare
- Survival rate by gender
- Survival rate by class

### 5. Multivariate Analysis
- Correlation heatmap
- Pairplot
- Survival rate by gender and passenger class

### 6. Feature Engineering
A new feature was created:

```python
FamilySize = SibSp + Parch + 1
