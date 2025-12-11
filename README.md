# How Random Forest Hyperparameters Shape Decision Boundaries  
Breast Cancer Wisconsin (Diagnostic) Dataset

This repository contains a tutorial and supporting code that explore how Random Forest hyperparameters, feature importance techniques, and dimensionality-reduction methods influence model behaviour and decision boundaries when applied to the Breast Cancer Wisconsin dataset.

## Contents

- `tutorial.pdf`: Main tutorial document explaining the concepts, workflow, results, and interpretations.
- `notebooks/`: Jupyter or Colab notebook containing the full code workflow.
- `src/`: Python scripts used for training models, generating plots, and running experiments.
- `figures/`: Directory containing all generated plots (EDA, PCA, NCA, decision boundaries, hyperparameter effects, GridSearchCV results, etc.).
- `LICENSE`: Licensing information.
- `requirements.txt`: Python dependencies.

## What this tutorial covers

This tutorial walks through a complete classical ML workflow:
- Loading and exploring the Breast Cancer dataset  
- Visual EDA (class distribution, boxplots, correlation matrix)  
- Feature importance  
  - Gini importance  
  - Permutation importance  
- Decision boundary visualisation using:
  - Top raw features  
  - PCA (unsupervised projection)  
  - NCA (supervised projection)  
- Hyperparameter studies for:
  - `max_depth`, `n_estimators`, `max_features`, `min_samples_leaf`, `min_samples_split`
- GridSearchCV hyperparameter tuning  
- Final model evaluation and confusion matrix  

The goal is to illustrate how Random Forests behave under different modelling choices and how visualisation can support interpretation.

## How to use

1. Install dependencies from `requirements.txt`.
2. Run the notebook in `notebooks/` or execute scripts in `src/` to regenerate all figures.
3. Open `tutorial.pdf` to read the full explanation.

You may also run the notebook in Google Colab for an interactive version of the tutorial.
