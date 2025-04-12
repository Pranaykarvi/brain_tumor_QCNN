# 🧠 Brain Tumor Detection using Quantum Convolutional Neural Networks (QCNN)

This project demonstrates the use of **Quantum Convolutional Neural Networks (QCNN)** to classify MRI brain scans into tumor and non-tumor categories. It blends classical deep learning with quantum computing to enhance diagnostic accuracy while minimizing the number of parameters.

## Overview

- **Objective:** Binary classification of brain MRI images.
- **Methodology:** Classical CNN + Quantum layer using Pennylane and PyTorch.
- **Dataset:** Brain MRI Images (Tumor vs Non-Tumor).

##  Tech Stack

- Python
- PyTorch
- Pennylane (for quantum circuit integration)
- NumPy, PIL, Matplotlib

##  Workflow

1. **Data Preprocessing**
   - Resize to 64x64
   - Normalize pixel values
   - Train-test split

2. **Model Architecture**
   - Classical CNN layers
   - Quantum Layer using Pennylane
   - Fully connected layers for classification

3. **Training**
   - CrossEntropyLoss
   - Adam Optimizer
   - Epoch-wise accuracy and loss tracking

## Results

- QCNN model demonstrated competitive performance with reduced parameter count.
- Visualized confusion matrix and training metrics.



## 📚 References

- [Pennylane](https://pennylane.ai/)
- [Quantum ML Overview](https://qiskit.org/learn/)

## 📎 Notebook

👉 [View on Kaggle](https://www.kaggle.com/code/pranaykarvi/brain-tumor-qcnn)
