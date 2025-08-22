# Anomaly-and-Perceptron-Study

This repository contains the Jupyter notebook `Anomaly-and-Perceptron-Study.ipynb` for Anomaly-and-Perceptron-Study, which is divided into two parts:

##  Part 1: Anomaly Detection
Anomaly detection using:
- **Isolation Forest**
- **Local Outlier Factor (LOF)**

##  Part 2: Neural Networks (Simple Perceptron)
Performance evaluation of a basic perceptron on two synthetic datasets:
- **SeaSyn** dataset (linearly separable)
- **RingSyn** dataset (non-linearly separable)

---

##  Files Included

| File                          | Description                                      |
|-------------------------------|--------------------------------------------------|
| `Anomaly-and-Perceptron-Study.ipynb`| Main notebook containing all required code |
| `GenSyn2122.csv`              | Input data for Part 1                            |
| `GenSyn_labels2122.csv`       | Ground truth labels for Part 1                   |
| `SeaSynTrain.csv`             | Training data for Part 2(a)                      |
| `SeaSynTest.csv`              | Testing data for Part 2(a)                       |
| `RingSynTrain.csv`            | Training data for Part 2(b)                      |
| `RingSynTest.csv`             | Testing data for Part 2(b)                       |

---

##  How to Run

###  Environment Requirements
- Python ≥ 3.8
- Jupyter Notebook

###  Install Required Packages

Before running the notebook, install the required Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib

