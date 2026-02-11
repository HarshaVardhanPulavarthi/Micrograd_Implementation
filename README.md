Building Micrograd: A Step-by-Step Neural Network Engine This repository contains a walkthrough of building a custom autograd (automatic gradient) engine and a neural network library from scratch. The implementation is heavily inspired by Andrej Karpathy's "The spelled-out intro to neural networks: building micrograd."

📺 Recommended Resource For the best learning experience, it is highly recommended to code along with the original video: YouTube: Building Micrograd by Andrej Karpathy

🚀 Overview The notebook guides you through the fundamental building blocks of modern Deep Learning, including:

The Value Object: Building a scalar-valued engine that tracks the computation graph.

Manual Backpropagation: Understanding how the Chain Rule flows through addition, multiplication, and activation functions.

Automatic Differentiation: Implementing the .backward() function to automate gradient calculations.

Neuron, Layer, and MLP Classes: Constructing a modular multi-layer perceptron.

Optimization: Writing a training loop to perform Gradient Descent and minimize loss.

🧠 Approach The code is written step-by-step and is specifically optimized for readability. Whether you are a beginner looking to understand the "magic" behind PyTorch or an experienced developer brushing up on the fundamentals, you can follow this notebook with ease.

🛠️ Usage Open the .ipynb notebook.

Follow the cells sequentially to build the engine from the ground up.

Play with the weights and learning rates in the final section to see the network converge on a dataset.

💡 Features Included Mathematical Intuition: Every major function includes a section explaining the "Why" behind the math.

Visualizations: Logic for understanding the flow of data through neurons and layers.
