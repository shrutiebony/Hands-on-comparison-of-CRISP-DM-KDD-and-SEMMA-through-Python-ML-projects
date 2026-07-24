# SEMMA: Iris Flower Species Classification

Classify **Iris flower species** from sepal and petal measurements using the **SEMMA** methodology (Sample, Explore, Modify, Model, Assess). A Random Forest classifier is trained and evaluated on the well-known Iris dataset.

## Problem Statement

Given four numeric features—sepal length, sepal width, petal length, and petal width—predict which of three Iris species a flower belongs to: *Setosa*, *Versicolor*, or *Virginica*.

## Dataset

**Iris Dataset**  
- 150 samples, 50 per species  
- Features: sepal length/width, petal length/width (cm)  
- Source file used in the notebook: `Iris.csv`

## Methodology Mapping

| SEMMA Step | What This Project Does |
|------------|------------------------|
| Sample | Loads the Iris dataset and creates stratified train/test splits |
| Explore | Visualizes feature distributions, correlations, and species separability |
| Modify | Scales features and prepares data for modeling |
| Model | Trains a **Random Forest Classifier** (`n_estimators=100`) |
| Assess | Reports accuracy, classification report, and confusion matrix |

## Models & Tools

- **Random Forest Classifier** (scikit-learn)
- **Python stack:** pandas, matplotlib, seaborn, scikit-learn

## Contents

| File | Description |
|------|-------------|
| `SEMMA_Iris_Classification_.ipynb` | Full SEMMA workflow notebook |
| `SEMMA.pdf` | Written report documenting the project |
| `research_paper_latex_source` | LaTeX source for the research paper |

## How to Run

1. Obtain the Iris dataset (`Iris.csv`) or use `sklearn.datasets.load_iris()`.
2. Open `SEMMA_Iris_Classification_.ipynb` in Jupyter or Google Colab.
3. Install dependencies: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.
4. Update the data path if not running in Colab (replace `/content/Iris.csv`).

## Expected Results

The Random Forest model typically achieves high accuracy on this dataset due to strong linear separability between species—especially Setosa versus the other two classes.

## Related Writing

[CRISP-DM, SEMMA, and KDD — Medium article](https://medium.com/@shrutiebony/crisp-dm-semma-and-kdd-6244a4661e04)
