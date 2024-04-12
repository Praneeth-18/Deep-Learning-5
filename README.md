[YouTube Link]([https://youtu.be/BasLSbv9YGk](https://youtu.be/vym_r3TOWko))

# Neural Network Implementations Across Different Frameworks

This repository contains a series of neural network implementations demonstrating the construction and training of a 3-layer deep neural network for non-linear regression across different programming frameworks and methodologies. These implementations serve as an educational resource to understand the basics and intricacies of neural network development from scratch, as well as utilizing high-level APIs for streamlined development. Each implementation focuses on a different approach or framework, including NumPy, PyTorch, TensorFlow, and JAX.

## Implementations Overview

### A. NumPy-based Implementation (From Scratch)
- Developed a 3-layer deep neural network purely using NumPy.
- Implemented manual backpropagation and gradient propagation through the chain rule.
- Activation functions and neuron counts in hidden layers were carefully chosen to suit non-linear regression tasks.
- The training process, loss reduction, and final output predictions were demonstrated.

### B. PyTorch Implementations
1. **From Scratch Implementation:**
   - Constructed a 3-layer neural network using low-level PyTorch operations without relying on PyTorch's built-in layer functionalities.
   - Manual implementation of backpropagation for understanding fundamental operations.
   
2. **Class-based Implementation Using Built-in Functionality:**
   - Utilized PyTorch's high-level APIs to define the neural network through a class, incorporating built-in layers, loss functions, and optimization methods.
   
3. **PyTorch Lightning Version:**
   - Leveraged PyTorch Lightning to simplify the boilerplate code required for model training, validation, and testing, showcasing a more efficient development process.

### C. TensorFlow Implementations
1. **Low-level API Implementation (From Scratch):**
   - Illustrated the building of the neural network using TensorFlow's low-level APIs, emphasizing the manual construction and optimization process.
   
2. **Implementation with Built-in Layers:**
   - Adopted TensorFlow's built-in layers to compose the neural network, demonstrating a balance between customization and efficiency.
   
3. **Functional API Usage:**
   - Employed TensorFlow's Functional API to define the model, showcasing an alternative approach to model architecture design that is both powerful and flexible.
   
4. **High-level API Utilization:**
   - Showcased the use of TensorFlow's high-level APIs for rapid development and training of neural networks, emphasizing simplicity and convenience.

### D. JAX Implementation
- Replicated the neural network using JAX for numerical computations and Flax for model definition, to highlight the capabilities of JAX in performing automatic differentiation and its compatibility with GPU/TPU acceleration.

## Getting Started
To run these implementations, ensure you have the required dependencies installed for each framework:
- NumPy
- PyTorch and PyTorch Lightning
- TensorFlow
- JAX and Flax

