# Building Micrograd: A Step-by-Step Neural Network Engine

This repository contains a comprehensive guide to building a custom autograd (automatic gradient) engine and a neural network library from scratch. The implementation is heavily inspired by **Andrej Karpathy's** "The spelled-out intro to neural networks: building micrograd."

### 📺 Recommended Resource
For the best learning experience, it is highly recommended to code along with the original video:
**[YouTube: Building Micrograd by Andrej Karpathy](https://www.youtube.com/watch?v=VMj-3S1tku0)**

---

## 🚀 Overview
The notebook guides you through the fundamental building blocks of modern Deep Learning, including:

* **The `Value` Object**: Building a scalar-valued engine that tracks the computation graph.
* **Manual Backpropagation**: Understanding how the Chain Rule flows through addition, multiplication, and activation functions.
* **Automatic Differentiation**: Implementing the `.backward()` function to automate gradient calculations.
* **Neuron, Layer, and MLP Classes**: Constructing a modular multi-layer perceptron.
* **Optimization**: Writing a training loop to perform Gradient Descent and minimize loss.



---

## 🧠 Approach
The code in this repository is designed to be **step-wise and beginner-friendly**.
* **Educational Flow**: Concepts are introduced one by one, ensuring you understand the "why" before moving to the "how."
* **Readability**: The implementation is optimized for clarity, making it accessible even if you are new to neural networks.
* **Hands-on Learning**: Even if you choose to follow this notebook independently of the video, the logic is self-contained and easy to follow.

## 🛠️ Usage
1.  Open the `.ipynb` notebook.
2.  Execute the cells sequentially to build the engine from the ground up.
3.  Experiment with the weights and learning rates in the final section to observe how the network converges on a dataset.

---

## 💡 Key Features
* **Mathematical Intuition**: Every major function includes a section explaining the underlying calculus.
* **Gradient Descent**: A practical demonstration of how weights are updated to reduce error.
