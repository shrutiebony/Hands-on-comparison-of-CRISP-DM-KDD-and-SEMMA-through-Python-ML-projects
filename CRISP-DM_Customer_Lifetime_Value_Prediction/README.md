# CRISP-DM: Customer Lifetime Value Prediction (Online Retail)

Predict **Customer Lifetime Value (CLV)** from transactional retail data using the **CRISP-DM** methodology. The workflow walks through all six CRISP-DM phases on the **Online Retail II** dataset—from business framing and exploratory analysis to model training, evaluation, and deployment artifacts.

## Business Problem

Retail businesses need to identify high-value customers to prioritize retention, marketing spend, and loyalty programs. This project builds regression models that estimate how much revenue a customer is likely to generate over their relationship with the store.

## Dataset

**Online Retail II** — UCI machine learning repository  
- Transaction-level records with customer IDs, product descriptions, quantities, prices, and invoice dates  
- Source file used in the notebook: `online_retail_II.xlsx`

## Methodology Mapping

| CRISP-DM Phase | What This Project Does |
|----------------|------------------------|
| Business Understanding | Defines CLV as the prediction target and frames the retail use case |
| Data Understanding | Loads transactions, summarizes shape, and runs exploratory data analysis |
| Data Preparation | Cleans missing customer IDs, aggregates per-customer features, handles outliers |
| Modeling | Trains Random Forest and neural network regressors; tunes hyperparameters with cross-validation |
| Evaluation | Compares models with regression metrics and residual analysis |
| Deployment | Saves the trained model (`clv_model.h5`) for downstream use |

## Models & Tools

- **Random Forest Regressor** (scikit-learn) with hyperparameter search
- **Neural network regressor** (Keras/TensorFlow)
- **Python stack:** pandas, matplotlib, seaborn, scikit-learn, TensorFlow

## Contents

| File | Description |
|------|-------------|
| `CustomerLifetimeValue_CRISP_DM.ipynb` | Full CRISP-DM workflow notebook |
| `Research_paper_CRISP_DM.pdf` | Written report documenting the project |
| `research_paper_latex_source` | LaTeX source for the research paper |

## How to Run

1. Download [Online Retail II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) and place `online_retail_II.xlsx` where the notebook can read it.
2. Open `CustomerLifetimeValue_CRISP_DM.ipynb` in Jupyter or Google Colab.
3. Install dependencies: `pandas`, `openpyxl`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`.
4. Update the data path if not running in Colab (replace `/content/online_retail_II.xlsx`).

## Related Writing

[CRISP-DM, SEMMA, and KDD — Medium article](https://medium.com/@shrutiebony/crisp-dm-semma-and-kdd-6244a4661e04)
