# Data Mining Methodologies in Practice — CMPE 255

This repository compares three widely used data mining and machine learning workflows—**CRISP-DM**, **KDD**, and **SEMMA**—through hands-on Python projects. Each project applies one methodology end-to-end on a real dataset, from data exploration through model evaluation and documentation.

## Projects

| Folder | Methodology | Use Case | Dataset |
|--------|-------------|----------|---------|
| [CRISP-DM_Customer_Lifetime_Value_Prediction](CRISP-DM_Customer_Lifetime_Value_Prediction/) | CRISP-DM | Predict customer lifetime value (CLV) for retail | Online Retail II |
| [KDD_Titanic_Survival_Prediction](KDD_Titanic_Survival_Prediction/) | KDD | Binary classification of passenger survival | Titanic |
| [SEMMA_Iris_Species_Classification](SEMMA_Iris_Species_Classification/) | SEMMA | Multi-class flower species classification | Iris |

## Methodology Overview

### CRISP-DM (Cross-Industry Standard Process for Data Mining)

A six-phase, business-oriented process that is iterative and adaptable:

1. **Business Understanding** — Define objectives, success criteria, and project plan
2. **Data Understanding** — Collect, describe, explore, and assess data quality
3. **Data Preparation** — Clean, transform, and engineer features for modeling
4. **Modeling** — Select algorithms, train models, and tune hyperparameters
5. **Evaluation** — Validate results against business goals
6. **Deployment** — Deliver insights via reports, dashboards, or production systems

### KDD (Knowledge Discovery in Databases)

A six-stage pipeline focused on extracting actionable knowledge from data:

1. **Data Selection** — Identify relevant data sources
2. **Data Preprocessing** — Handle noise, missing values, and inconsistencies
3. **Data Transformation** — Format and structure data for mining
4. **Data Mining** — Apply algorithms to discover patterns
5. **Pattern Evaluation** — Assess and interpret discovered knowledge
6. **Knowledge Representation** — Present findings in an understandable form

### SEMMA (Sample, Explore, Modify, Model, Assess)

SAS's five-step model-building cycle:

1. **Sample** — Select representative training and test data
2. **Explore** — Perform EDA to uncover trends and relationships
3. **Modify** — Clean, transform, and scale features
4. **Model** — Build and train predictive models
5. **Assess** — Evaluate performance with metrics and visualizations

## Repository Structure

```
.
├── CRISP-DM_Customer_Lifetime_Value_Prediction/
│   ├── CustomerLifetimeValue_CRISP_DM.ipynb
│   ├── Research_paper_CRISP_DM.pdf
│   └── research_paper_latex_source
├── KDD_Titanic_Survival_Prediction/
│   ├── Titanic_Survival_Prediction_KDD.ipynb
│   ├── Research_paper_KDD.pdf
│   └── research_paper_latex_source
├── SEMMA_Iris_Species_Classification/
│   ├── SEMMA_Iris_Classification_.ipynb
│   ├── SEMMA.pdf
│   └── research_paper_latex_source
└── README.md
```

## Getting Started

Each project folder contains its own README with dataset requirements, methodology mapping, and notebook instructions. Notebooks were developed for Google Colab; update file paths (e.g., `/content/...`) when running locally.

## Related Writing

A companion overview of these three methodologies is available on Medium:  
[CRISP-DM, SEMMA, and KDD](https://medium.com/@shrutiebony/crisp-dm-semma-and-kdd-6244a4661e04)

## Course

Developed for **CMPE 255** — Data Mining and Machine Learning.
