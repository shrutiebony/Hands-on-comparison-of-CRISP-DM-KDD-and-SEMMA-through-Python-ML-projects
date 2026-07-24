# KDD: Titanic Passenger Survival Prediction

Apply the **Knowledge Discovery in Databases (KDD)** process to predict whether a **Titanic passenger survived**, using the classic Titanic dataset. Each KDD stage—from data selection through knowledge representation—is implemented step by step in Python.

## Problem Statement

Given passenger attributes (ticket class, age, sex, fare, family size, etc.), build a classifier that predicts survival (`Survived`: 0 or 1). This is a standard introductory binary classification task well suited to demonstrating the full KDD pipeline.

## Dataset

**Titanic — Machine Learning from Disaster** (Kaggle)  
- 891 training records with features such as `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`  
- Target variable: `Survived`

## Methodology Mapping

| KDD Stage | What This Project Does |
|-----------|------------------------|
| Data Selection | Loads the Titanic dataset and selects relevant passenger features |
| Data Preprocessing | Handles missing values (e.g., Age, Embarked) and encodes categorical variables |
| Data Transformation | Splits features and target; prepares train/test partitions |
| Data Mining | Trains a **Logistic Regression** classifier |
| Pattern Evaluation | Measures accuracy and inspects model performance on held-out data |
| Knowledge Representation | Summarizes findings and model behavior for interpretation |

## Models & Tools

- **Logistic Regression** (scikit-learn)
- **Python stack:** pandas, scikit-learn

## Contents

| File | Description |
|------|-------------|
| `Titanic_Survival_Prediction_KDD.ipynb` | Full KDD workflow notebook |
| `Research_paper_KDD.pdf` | Written report documenting the project |
| `research_paper_latex_source` | LaTeX source for the research paper |

## How to Run

1. Download the [Titanic dataset](https://www.kaggle.com/c/titanic/data) (`train.csv`).
2. Open `Titanic_Survival_Prediction_KDD.ipynb` in Jupyter or Google Colab.
3. Install dependencies: `pandas`, `scikit-learn`.
4. Point the notebook to your local copy of the CSV if not using Colab.

## Related Writing

[CRISP-DM, SEMMA, and KDD — Medium article](https://medium.com/@shrutiebony/crisp-dm-semma-and-kdd-6244a4661e04)
