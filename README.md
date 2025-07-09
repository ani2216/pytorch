# 📄 Lecture - 0: Fundamentals of PyTorch 🧑‍💻🔥

Welcome to **Lecture 0** of the **PyTorch series**. This notebook provides a comprehensive introduction to **PyTorch**, one of the most popular and powerful deep learning frameworks used in research and production today.

This hands-on tutorial is designed for **absolute beginners** who are new to **PyTorch**, **Machine Learning**, and **Deep Learning**. The lecture covers the **essential building blocks of PyTorch** through simple code examples and explanations.

---

## 🚀 What You'll Learn

### 🔧 1. Setting Up the Environment
- Checking **GPU availability** in **Google Colab** using:
  ```python
  !nvidia-smi
Installing and importing essential Python libraries:

* torch — for deep learning
* numpy — for numerical computing
* pandas — for data handling

🔢 2. PyTorch Tensors
Understanding what Tensors are and how they form the foundation of PyTorch computations.

Creating tensors using:

*python
*Copy
*Edit
*torch.tensor()
*torch.zeros()
*torch.ones()
*torch.rand()
Checking tensor properties:

.shape

.dtype

.device

Performing tensor operations:

Addition, subtraction, multiplication, division

Matrix multiplication using:

python
Copy
Edit
torch.mm()
# or
@
Reshaping tensors using:

python
Copy
Edit
tensor.view()
tensor.reshape()
📈 3. Basic Data Visualization
Visualizing numerical data using Matplotlib.

Plotting simple graphs to explore data and trends.

🔄 4. Introduction to Autograd (Automatic Differentiation)
Concept of automatic gradient computation in PyTorch using:

python
Copy
Edit
x = torch.tensor(2.0, requires_grad=True)
y = x ** 3
y.backward()
print(x.grad)
How PyTorch builds and computes gradients automatically for complex computations.

Hands-on practice with .backward() and .grad.

💡 Key Takeaways
Understand the core data structure: PyTorch Tensors.

Perform basic tensor manipulations and operations.

Learn to visualize data and compute gradients—the first step towards building deep learning models.

📌 Running the Notebook
It is recommended to run this notebook in Google Colab with GPU acceleration for the best performance.

Check GPU availability using:

python
Copy
Edit
!nvidia-smi
🔗 Notebook: 0_Pytorch.ipynb
