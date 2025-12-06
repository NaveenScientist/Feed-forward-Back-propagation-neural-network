# Feed Forward Neural Network & Backpropagation – Deep Learning Project
# Overview

This project demonstrates the complete implementation of a Feed Forward Neural Network (FNN) and Backpropagation algorithm from scratch using Python and NumPy.
Instead of relying on deep learning libraries such as TensorFlow or PyTorch, the network is manually constructed to provide a clear understanding of core neural network mechanics, including forward pass, loss computation, weight updates, and convergence behavior.

The primary objective of this project is to explore how neural networks learn by minimizing loss through gradient descent and optimizing internal weights during training.

# Project Highlights

Built a fully functioning neural network from scratch without auto-grad frameworks.

Implemented forward propagation, loss function, and backpropagation using gradient descent.

Applied activation functions (ReLU / Sigmoid / Softmax based on dataset requirement).
<Figure size 1400x1000 with 6 Axes><img width="1398" height="989" alt="image" src="https://github.com/user-attachments/assets/c79bf530-5a7b-4278-bd28-82563655c7f9" />

Visualized loss curve, training convergence, and prediction performance.
<img width="375" height="494" alt="Model Loss" src="https://github.com/user-attachments/assets/175a3938-fe7a-4d95-9581-dfd02edd5e2a" />

<img width="470" height="502" alt="Model Accuracy" src="https://github.com/user-attachments/assets/13fcb608-ef3f-48a8-8053-7f07bfffdfae" />

Compared manual neural network learning with Scikit-learn MLPClassifier as a benchmark.

# Workflow

Data Preprocessing

Weight & Bias Initialization

Forward Propagation

Loss Calculation

Backpropagation

Gradient Descent Optimization

Training & Evaluation

# Results

Achieved consistent loss minimization across epochs with stable weight updates.

Demonstrated successful training convergence indicating correct gradient flow.

Model generalized well for unseen data, showing strong classification accuracy (dataset-dependent).

This project strengthens conceptual understanding of how modern deep learning frameworks operate internally.

# Tech Stack
Component	Tools
Language	Python
Libraries	NumPy, Pandas, Matplotlib, Scikit-learn (for benchmarking)
Concepts	Neural Networks, Backpropagation, Gradient Descent, Activation Functions


# Future Scope

Add support for multiple hidden layers (Deep Fully Connected Networks).

Integrate regularization methods (L2, dropout) to prevent overfitting.

Extend to mini-batch gradient descent & adaptive learning rate optimizers (Adam, RMSProp).

Transform model to PyTorch / TensorFlow version for deployment.
