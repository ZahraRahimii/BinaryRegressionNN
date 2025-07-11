# BinaryRegressionNN

### Project Overview

1. **Data Loading & Preprocessing**

   * Load the **[Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris)** and filter it to only two classes: *Setosa* and *Versicolor*.
   * Normalize the features to a \[0, 1] range.

2. **Logistic Regression (Binary Classification)**

   * Implement logistic regression using **Sigmoid activation**.
   * Use **Cross-Entropy Loss** for training.
   * Optimize the model using **gradient descent**.

3. **Two-Layer Neural Network**

   * Build a simple feed-forward neural network with **one hidden layer** using **ReLU** activation.
   * Use **Sigmoid** in the output layer for binary probability prediction.

4. **Evaluation Metrics**

   * Evaluate models using:

     * **Accuracy**
     * **Precision**
     * **Recall**
     * **F1 Score**
   * Compare metrics across models.

5. **Loss Curve & Overfitting**

   * Plot training/test loss over epochs.
   * Investigate the effects of **overfitting** and **underfitting**.
   * Study model behavior by changing:

     * Learning rate
     * Number of hidden units
     * Number of layers
     * Regularization (Dropout, L2)

6. **Experiment Tracking**

   * Use **W\&B** and **Comet.ml** for:

     * Logging metrics
     * Visualizing model performance
     * Comparing different hyperparameters
