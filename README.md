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

z = w · x + b

Where:

- **w** = weight vector  
- **x** = input vector  
- **b** = bias  

The prediction rule is:

y = 1  if z > 0  
y = -1 if z ≤ 0

---

# Weight Update Rule

When the prediction is incorrect, the weights and bias are updated using the perceptron learning rule:

w = w + η * y * x  
b = b + η * y

Where:

- **η (eta)** = learning rate  
- **y** = true label  
- **x** = input vector  

---

# Training Process

1. Initialize weights and bias.
2. For each training example, compute the linear output.
3. Predict the class label.
4. Update weights and bias if the prediction is incorrect.
5. Repeat for multiple epochs until the model converges.

---

# Conclusion

The perceptron successfully learns the **AND gate classification problem** by adjusting its weights and bias through iterative updates. This demonstrates the fundamental concept of learning in neural networks.
