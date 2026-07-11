# Assignment 1: Plotting Activation Functions

## Aim
To implement and visualize commonly used activation functions in Artificial Neural Networks (ANN) using Python.

## Concept

Activation functions introduce **non-linearity** into a neural network, enabling it to learn complex patterns and relationships in data. Without activation functions, a neural network would behave like a simple linear model regardless of the number of layers.

### Activation Functions Used

### 1. Sigmoid
- Maps input values to the range (0, 1).
- Commonly used for binary classification.
- Formula:
  σ(x) = 1 / (1 + e⁻ˣ)

### 2. Tanh
- Maps input values to the range (-1, 1).
- Zero-centered, making training more efficient than Sigmoid in many cases.

### 3. ReLU (Rectified Linear Unit)
- Returns 0 for negative inputs and the input itself for positive values.
- Most widely used activation function in deep learning because it is computationally efficient.

### 4. Leaky ReLU
- A variation of ReLU that allows a small gradient for negative inputs.
- Helps prevent the "dying ReLU" problem.

### 5. Softmax
- Converts a vector of values into probabilities that sum to 1.
- Commonly used in the output layer of multi-class classification models.

## Technologies Used
- Python
- NumPy
- Matplotlib

## Learning Outcome
- Understood the role of activation functions in neural networks.
- Compared the behavior of different activation functions.
- Learned to visualize mathematical functions using Matplotlib.