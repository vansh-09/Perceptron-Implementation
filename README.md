# Perceptron from Scratch (AND Gate)

A foundational neural network implementation based on the classic Perceptron model that learns to classify binary AND logic.

---


## What is a Perceptron?
A perceptron is the most basic building block of a neural network. It takes multiple binary inputs, multiplies them with weights, adds a bias, and passes them through a step function.

---

## Model Description
```
Inputs      : 2 (binary: 0 or 1)
Output      : 1 (either 0 or 1)
Activation  : Step function
Training    : Perceptron Learning Rule
```

---

## Perceptron Learning Rule

\[ y = f(w \cdot x + b) \]
\[ \text{if } y \neq target:\quad w = w + \eta (target - y) x \]

---

## Training Data (AND Gate)
```python
X = [[0, 0],
     [0, 1],
     [1, 0],
     [1, 1]]

Y = [0, 0, 0, 1]
```

---

## Code Breakdown
- Weight initialization
- Prediction using step function
- Training using simple update rule

---

## Final Output
```
Prediction after training:
[0, 0] → 0
[0, 1] → 0
[1, 0] → 0
[1, 1] → 1
```

---

## Key Learning Points
- Understand how logic gates can be learned
- How bias allows the perceptron to shift decision boundaries
- What the limitation of a single-layer perceptron is (cannot solve XOR)

---

Want to learn more? Try extending this to OR / NAND gates or multi-layer perceptrons.
