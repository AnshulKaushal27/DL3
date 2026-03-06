# Perceptron Learning Algorithm Implementation

This project demonstrates a simple implementation of the **Perceptron Learning Algorithm** using Python and NumPy.

The perceptron is trained to classify the **AND logic gate** dataset using supervised learning.

---

# What is a Perceptron?

A **Perceptron** is one of the earliest and simplest types of artificial neural networks.  
It is a **binary linear classifier** that separates data into two classes using a linear decision boundary.

The perceptron learns by adjusting its **weights and bias** based on classification errors during training.

---

# Dataset

The model is trained using the **AND gate dataset**:

| Input 1 | Input 2 | Output |
|-------|-------|-------|
| 0 | 0 | -1 |
| 0 | 1 | -1 |
| 1 | 0 | -1 |
| 1 | 1 | 1 |

Where:

- **-1** represents False  
- **1** represents True

---

# Perceptron Model

The perceptron computes the output using the linear function:
