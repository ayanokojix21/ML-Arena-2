# ML Arena 2 - Logistic Regression

This folder is a dedicated repo-style package for Problem 2: Logistic Regression.

This repository is part of the ML Arena family, a set of 5 dedicated repositories where each repository focuses on one core ML problem.

## ML Arena Family Repositories

- ML-Arena-1 - Linear Regression
- **ML-Arena-2 - Logistic Regression (Current Repo)**
- ML-Arena-3 - Decision Tree
- ML-Arena-4 - K-Means Clustering
- ML-Arena-5 - Neural Network

## Problem Focus

Build and analyze a binary classification model to predict diabetes outcome.

## Dataset

- File: `dataset.csv`
- Source: Pima Indians Diabetes Dataset (UCI)
- Rows: 768
- Columns: 9 (8 input features + 1 label)
- Target: `Outcome`

## Repository Layout

```
ML-Arena-2/
|- README.md
|- CONTRIBUTING.md
|- dataset.csv
|- exploration/exploration.ipynb
|- library/training.ipynb
|- scratch/training.ipynb
`- .github/PULL_REQUEST_TEMPLATE.md
```

## Task Tracks

- Exploration: Class balance, feature behavior, and data quality.
- Library: Baseline logistic model with standard libraries.
- Scratch: Sigmoid + loss + gradient descent using NumPy.
- Optimization: Improve baseline using threshold tuning, regularization, or class weighting.

## Quick Start

1. Fork this folder as its own repo (ML-Arena-2).
2. Clone your fork and create a branch.
3. Pick one issue.
4. Work in only one notebook based on track:
   - `exploration/exploration.ipynb`
   - `library/training.ipynb`
   - `scratch/training.ipynb`
5. Run all cells top to bottom.
6. Open a pull request with `Closes #<issue-number>`.

See `CONTRIBUTING.md` for detailed rules.
