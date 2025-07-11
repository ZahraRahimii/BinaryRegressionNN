# BinaryRegressionNN

### 🧠 Project Overview

This project implements a simple **binary logistic regression** model and a **two-layer neural network** using NumPy from scratch. The main steps are as follows:

* **Dataset**: The [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) is used for binary classification. For simplicity, only the *Setosa* and *Versicolor* classes are selected.
* **Data Preparation**: The dataset is visualized, normalized (if needed), and split into training and testing sets.
* **Loss Function**: **Cross-Entropy Loss** is used for model evaluation and optimization.
* **Evaluation Metrics**: Includes **Accuracy**, **Precision**, **Recall**, and **F1 Score**.
* **Visualization**: Training/testing loss curves and performance under different hyperparameters, dataset sizes, and learning rates.
* **Experiment Tracking**: Integrates with **Weights & Biases (wandb)** and **Comet.ml** for experiment tracking and result analysis.
