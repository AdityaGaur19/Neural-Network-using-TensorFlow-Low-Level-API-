# Neural Network using TensorFlow Low-Level API

A hands-on implementation of a neural network built from scratch using TensorFlow’s low-level (v1-style) API. This project focuses on understanding the core mechanics of neural networks without relying on high-level abstractions like Keras.

---

## Overview

This repository demonstrates how a simple feedforward neural network can be implemented using TensorFlow’s computational graph approach. The model is trained on the classic XOR problem, which is a fundamental example used to showcase the power of neural networks in handling non-linear patterns.

---

## Key Features

- Built using TensorFlow low-level API (no Keras)
- Manual implementation of:
  - Placeholders
  - Variables (weights and biases)
  - Forward propagation
  - Loss computation (Mean Squared Error)
  - Gradient Descent optimization
- Demonstrates solving a non-linearly separable problem (XOR)
- Clean and minimal code for learning purposes

---

## Tech Stack

- Python  
- NumPy  
- TensorFlow (v1 compatibility mode)

---


---

## How It Works

1. Input data (XOR dataset) is defined manually  
2. Placeholders are created for inputs and outputs  
3. Weights and biases are initialized  
4. A hidden layer with sigmoid activation is used  
5. Output layer produces final predictions  
6. Loss is computed using Mean Squared Error  
7. Model is trained using Gradient Descent  
8. Predictions are printed after training  

---

## XOR Problem

| Input | Output |
|------|--------|
| 0, 0 |   0    |
| 0, 1 |   1    |
| 1, 0 |   1    |
| 1, 1 |   0    |

This problem cannot be solved using a linear model, making it ideal to demonstrate neural network capabilities.

---

## Installation & Setup

```bash
git clone git@github.com:AdityaGaur19/Neural-Network-using-TensorFlow-Low-Level-API-.git
cd Neural-Network-using-TensorFlow-Low-Level-API-

Step: 0 Loss: 0.25
Step: 2000 Loss: ...
Step: 4000 Loss: ...
...

Predicted Output:
[[~0]
 [~1]
 [~1]
 [~0]]
