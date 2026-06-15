# Hybrid Quantum Machine Learning for Multi-Class Image Classification

## Overview

This project explores the integration of Quantum Machine Learning (QML) and Deep Learning for image classification. A quantum feature extraction pipeline is developed using PennyLane and integrated with a classical neural network built using TensorFlow/Keras.

The objective is to investigate whether quantum-inspired feature representations can effectively capture image information while reducing dimensionality and maintaining strong classification performance.

---

## Key Features

✔ Quantum Image Preprocessing

✔ Hybrid Quantum-Classical Architecture

✔ Multi-Class Image Classification

✔ PennyLane Quantum Circuits

✔ TensorFlow/Keras Neural Network

✔ Dimensionality Reduction through Quantum Encoding

✔ Performance Evaluation using Accuracy, Precision, Recall and F1-Score

---

## Dataset

The dataset consists of four image classes.

| Split | Samples |
|---------|---------|
| Training | 4200 |
| Validation | 900 |
| Testing | 900 |

Original image size:

128 × 128 pixels

---

## Methodology

### 1. Image Preprocessing

Images are resized and normalized before being processed by the quantum feature extractor.

### 2. Quantum Feature Extraction

The quantum module performs:

- Angle Encoding
- Quantum Rotations
- Entanglement Operations
- Quantum Measurements

Implemented using:

```python
qml.device("lightning.qubit", wires=4)
```

The quantum circuit transforms image information into a compressed feature representation.

Input Resolution:

128 × 128

Output Resolution:

64 × 64

### 3. Hybrid Classification Network

The extracted quantum features are passed to a classical neural network.

Architecture:

Input Layer
↓
Flatten
↓
Dense(128, ReLU)
↓
Dropout(0.5)
↓
Dense(64, ReLU)
↓
Dropout(0.3)
↓
Dense(Output Classes, Softmax)

---

## Quantum Circuit

The feature extraction stage utilizes:

- 4-Qubit Quantum Circuit
- Parameterized Rotation Gates
- Entanglement Layers
- Expectation Value Measurements

The generated quantum features are subsequently used by the classical classifier.

---

## Results

### Model Performance

| Metric | Score |
|----------|----------|
| Training Accuracy | 93% |
| Validation Accuracy | 89% |
| Test Accuracy | 88-89% |

---

## Training Curves

![Training Accuracy](results/training_accuracy.png)

![Training Loss](results/training_loss.png)

---

## Confusion Matrix

![Confusion Matrix](results/confusion_matrix.png)

---

## Classification Report

![Classification Report](results/classification_report.png)

---

## Technologies Used

- Python
- TensorFlow
- Keras
- PennyLane
- NumPy
- Matplotlib
- Scikit-Learn

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Hybrid-Quantum-Image-Classification.git
```

Move into project directory:

```bash
cd Hybrid-Quantum-Image-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch the notebook:

```bash
jupyter notebook notebooks/final_code.ipynb
```

Or train directly:

```bash
python src/train.py
```

---

## Future Work

- Variational Quantum Classifiers (VQC)
- Quantum Transfer Learning
- Quantum Attention Mechanisms
- Quantum Federated Learning
- Execution on Real Quantum Hardware
- Comparison with Classical CNN Baselines

---

## Author

Shashank Kadarla

B.Tech Artificial Intelligence

Quantum Machine Learning Researcher

GATE DA Qualified

---

## Citation

If you use this work, please cite:

```bibtex
@misc{kadarla2026hqml,
  author = {Shashank Kadarla},
  title = {Hybrid Quantum Machine Learning for Multi-Class Image Classification},
  year = {2026},
  publisher = {GitHub}
}
```
