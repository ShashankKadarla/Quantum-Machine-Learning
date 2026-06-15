<div align="center">

# Quantum-Enhanced Image Classification

### Hybrid Quantum Machine Learning for Computer Vision using PennyLane and TensorFlow

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)]()
[![PennyLane](https://img.shields.io/badge/PennyLane-Quantum-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT-red.svg)]()

---

Exploring Quantum Feature Extraction for Multi-Class Image Classification through a Hybrid Quantum-Classical Learning Framework.

</div>

---

# Project Motivation

Deep Learning has revolutionized Computer Vision.

However, modern neural networks require:

- Large datasets
- Significant computational resources
- Millions of trainable parameters

Quantum Machine Learning (QML) offers a fundamentally different paradigm where information can be represented in exponentially large Hilbert spaces.

This project investigates whether quantum feature extraction can generate meaningful image representations before classical classification.

The central research question is:

> Can quantum-enhanced feature extraction improve image representation while reducing dimensionality and maintaining competitive classification performance?

---

# System Overview

<p align="center">
<img src="assets/architecture.png" width="850">
</p>

The proposed framework consists of:

1. Classical Image Processing
2. Quantum Feature Extraction
3. Hybrid Quantum Encoding
4. Classical Neural Classification

---

# Pipeline

Input Image

↓

Resize & Normalize

↓

Quantum Encoding

↓

Parameterized Quantum Circuit

↓

Quantum Measurement

↓

Feature Vector Generation

↓

Classical Neural Network

↓

Classification Output

---

# Quantum Feature Extraction

Unlike conventional CNN feature extraction, this work employs a quantum circuit for generating image representations.

The circuit performs:

### 1.Angle Encoding

Classical pixel values are encoded into quantum states using rotation gates.

### 2.Variational Quantum Layers

Parameterized quantum gates learn meaningful transformations in Hilbert space.

### 3.Entanglement Operations

Qubits exchange information through entanglement, allowing complex feature interactions.

### 4.Measurement

Expectation values are extracted and used as features for downstream classification.

---

# Quantum Circuit

<p align="center">
<img src="assets/quantum_circuit.png" width="800">
</p>

Configuration:

| Parameter | Value |
|------------|---------|
| Qubits | 4 |
| Backend | lightning.qubit |
| Framework | PennyLane |
| Measurements | Expectation Values |

---

# Hybrid Neural Architecture

```text
Input Features
      │
      ▼
Dense(128)
      │
    ReLU
      │
 Dropout(0.5)
      │
Dense(64)
      │
    ReLU
      │
 Dropout(0.3)
      │
 Softmax Output
```

The architecture combines quantum-derived representations with classical deep learning to create a hybrid learning system.

---

# Dataset

| Split | Samples |
|---------|---------|
| Training | 4200 |
| Validation | 900 |
| Testing | 900 |

Image Resolution:

128 × 128

Quantum Processed Resolution:

64 × 64

Classes:

4

---

# Experimental Results

## Training Performance

| Metric | Score |
|----------|----------|
| Training Accuracy | 93% |
| Validation Accuracy | 89% |
| Test Accuracy | 88-89% |

---

## Learning Curves

<p align="center">
<img src="assets/training_curves.png" width="800">
</p>

The model demonstrates stable convergence with minimal overfitting.

---

## Confusion Matrix

<p align="center">
<img src="assets/confusion_matrix.png" width="700">
</p>

---

## Sample Predictions

<p align="center">
<img src="assets/sample_predictions.png" width="800">
</p>

---

# Key Findings

### Quantum Compression

Quantum preprocessing reduced image dimensionality by approximately 75%.

### Stable Learning

The hybrid architecture maintained robust performance across all classes.

### Effective Feature Representation

Quantum-extracted features preserved discriminative information necessary for classification.

---

# Technologies

| Category | Tools |
|------------|---------|
| Quantum Computing | PennyLane |
| Deep Learning | TensorFlow |
| Neural Networks | Keras |
| Data Processing | NumPy |
| Visualization | Matplotlib |
| Evaluation | Scikit-Learn |

---

# Installation

Clone repository

```bash
git clone https://github.com/yourusername/Quantum-Enhanced-Image-Classification.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch notebook

```bash
jupyter notebook
```

---

# Future Research Directions

This project can be extended toward:

- Quantum Convolutional Neural Networks (QCNN)
- Variational Quantum Classifiers (VQC)
- Quantum Transfer Learning
- Quantum Attention Mechanisms
- Quantum Federated Learning
- Execution on Real Quantum Hardware
- Quantum Computer Vision Systems

---

# Research Contributions

This project demonstrates:

✓ Hybrid Quantum-Classical Learning

✓ Quantum Feature Engineering

✓ Quantum Dimensionality Reduction

✓ Computer Vision with Quantum Circuits

✓ End-to-End Quantum Machine Learning Workflow

---

# Author

### Shashank Kadarla

M.Tech, Quantum Computing @ DIAT - DRDO


GATE DA Qualified

Interested in:

- Quantum Machine Learning
- Computer Vision
- Deep Learning
- Reinforcement Learning
- Quantum Optimization

---

# Citation

```bibtex
@misc{kadarla2026quantumvision,
title={Quantum-Enhanced Image Classification},
author={Shashank Kadarla},
year={2026},
publisher={GitHub}
}
```
