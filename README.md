# CSCE 509 Pattern Recognition Homeworks

This repository contains four Google Colab notebooks for the CSCE 509 pattern-recognition homeworks. Each notebook implements and evaluates a different classification algorithm on synthetic datasets.

## Repository Structure

```
pattern-recognition-homeworks/
├── README.md
├── hw1/
│   └── hw1.ipynb      ← Perceptron and SVM experiments
├── hw2/
│   └── hw2.ipynb      ← Decision Tree experiments
├── hw3/
│   └── hw3.ipynb      ← k-Nearest Neighbors experiments
└── hw4/
    └── hw4.ipynb      ← Data generation, accuracy plots, and N=f(Q,P) fitting
```

## How to Run

All notebooks were developed in Google Colab and require no local setup:

| Notebook           | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `hw1/hw1.ipynb`    | Implement a Perceptron and various SVMs; evaluate via cross-validation      |
| `hw2/hw2.ipynb`    | Build and prune decision-tree classifiers on moon-shaped data               |
| `hw3/hw3.ipynb`    | Explore k-NN classification under varying noise levels                      |
| `hw4/hw4.ipynb`    | Generate datasets, plot accuracy vs. size/noise, model N=f(Q,P)             |
