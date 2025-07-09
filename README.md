# Lecture - 0: Fundamentals of PyTorch 🧑‍💻🔥
Welcome to Lecture 0 of the PyTorch series. This notebook provides a comprehensive introduction to PyTorch, one of the most popular and powerful deep learning frameworks used in research and production today.

This hands-on tutorial is designed for absolute beginners who are new to PyTorch, machine learning, and deep learning. The lecture covers the essential building blocks of PyTorch through simple code examples and explanations.

🚀 What You'll Learn:
🔧 1. Setting Up the Environment:
How to check GPU availability in Google Colab using:

python
Copy
Edit
!nvidia-smi
Installing and importing essential Python libraries:

torch for deep learning

numpy for numerical computing

pandas for data handling

matplotlib for visualization

🔢 2. PyTorch Tensors:
What are Tensors and how they form the foundation of PyTorch computations.

Creating tensors using:

torch.tensor()

torch.zeros()

torch.ones()

torch.rand()

Checking tensor properties:

.shape

.dtype

.device

Performing tensor operations:

Addition, subtraction, multiplication, division

Matrix multiplication (torch.mm or @ operator)

Reshaping tensors using .view() and .reshape()

📈 3. Basic Data Visualization:
Visualizing numerical data using Matplotlib.

Plotting simple graphs to understand data and trends.

🔄 4. Introduction to Autograd (Automatic Differentiation):
Concept of automatic gradient computation in PyTorch using:

python
Copy
Edit
x = torch.tensor(2.0, requires_grad=True)
y = x ** 3
y.backward()
print(x.grad)
How PyTorch builds and computes gradients automatically for complex computations.

Basic hands-on with .backward() and .grad.

💡 Key Takeaways:
Understand the core data structure (Tensor) of PyTorch.

Get comfortable with basic tensor manipulations and operations.

Learn to visualize data and compute gradients—the first step toward building deep learning models.

📌 Running the Notebook:
It is recommended to run this notebook in Google Colab with GPU acceleration for best performance.

Make sure to check GPU availability using !nvidia-smi before proceeding.

🔗 Notebook: 0_Pytorch.ipynb
🌱 What's Next:
This lecture sets the foundation for upcoming topics such as:

Building Neural Networks from scratch in PyTorch

Training models with real datasets

Implementing Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs)

Transfer Learning and more...

