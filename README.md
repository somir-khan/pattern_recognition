# CSCE 509 Pattern Recognition Homeworks

This repository contains four Google Colab notebooks for Pattern Recognition homeworks. Each notebook implements and evaluates a different classification algorithm on synthetic two-moons.

## Repository Structure

```
pattern-recognition-homeworks/
├── README.md
├── home_work_1.ipynb      ← Synthetic data generation; Perceptron, linear & non-linear SVM experiments
├── home_work_2.ipynb      ← Decision Tree noise and depth exploration
├── home_work_3.ipynb      ← k-NN performance under varying noise and k values
└── home_work_4.ipynb      ← KNN size-noise trade‑off and regression modeling of N=f(Q,P)
```

## How to Run

All notebooks were developed in Google Colab and require no local setup:

| Notebook                 | Description                                                                                                                                                        |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `home_work_1.ipynb`      | Generate synthetic two-class data (union of squares vs Gaussian), implement Perceptron and linear/non-linear SVMs with hyperparameter tuning, and evaluate via 4‑fold CV and a balanced test set. |
| `home_work_2.ipynb`      | Train and evaluate Decision Tree classifiers on two-moons data at noise levels 0.20 and 0.35; analyze bias-variance tradeoff by varying max depth and visualize decision boundaries.             |
| `home_work_3.ipynb`      | Examine k-Nearest Neighbors on two-moons datasets with noise 0.20 and 0.35; visualize decision boundaries for different k values and discuss the impact of noise and neighborhood size.        |
| `home_work_4.ipynb`      | Study KNN classifier performance as a function of training size and noise; quantify training-test accuracy gap and fit linear, polynomial, and decision-tree regressions to predict required dataset size. |
