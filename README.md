# Quantum Machine Learning Scripts 🧠⚛️

This repository contains a collection of Python scripts and modules related to **Quantum Machine Learning (QML)**. The focus is on foundational components and techniques including quantum neural networks, parameterized quantum circuits, quantum generative adversarial networks (qGANs), quantum kernel methods, and quantum data encoding strategies.

## 📁 Repository Structure

The repository is organized into the following main components:

- **`qnn/`**:  
  Scripts for building **Quantum Neural Networks (QNNs)**, including layers, loss functions, and basic models using frameworks like PennyLane or Qiskit Machine Learning.

- **`pqc/`**:  
  Implementations of **Parameterized Quantum Circuits (PQCs)** which serve as the core of many quantum learning models.

- **`qgan/`**:  
  A working implementation of **Quantum Generative Adversarial Networks**, demonstrating how quantum systems can be used to model probability distributions.

- **`kernels/`**:  
  Scripts related to **Quantum Kernel Methods**, such as the Quantum Kernel Estimation and classification via Support Vector Machines (QSVM).

- **`encoding/`**:  
  Techniques for **Quantum Data Encoding**, such as amplitude encoding, angle encoding, and basis encoding.

## 🔧 Dependencies

Make sure to install the following Python packages:

```bash
pip install numpy scipy matplotlib qiskit pennylane scikit-learn