# CapstoneProject
Fault Finding in tyres
# Capstone Project: FaultFindy

FaultFindy is an intelligent deep learning-based system designed to classify tyres as either defective or in good condition. By analyzing key manufacturing parameters and process data, this system achieves remarkable accuracy, aiding in quality assurance during tyre production.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

### Objective
The goal of this project is to develop a robust binary classification system to determine whether a tyre is defective or in good condition based on specific manufacturing data.

### Key Metrics
- Validation Accuracy: **96.12%**
- Model: **EfficientNetB4**

---

## Key Features

1. **Deep Learning Architecture**: Uses the EfficientNetB4 model for accurate classification.
2. **Binary Classification**: Identifies tyres as `defective` or `good`.
3. **Preprocessing**: Includes steps for data cleaning, normalization, and augmentation.
4. **Easy Deployment**: Model is ready for integration into quality control workflows.

---

## Dataset

- The dataset contains various manufacturing parameters and process data collected during tyre production.
- **Classes**:
  - `Defective`
  - `Good`
- Preprocessing steps include handling missing values, scaling, and data augmentation.

---

## Model Architecture

The project leverages **EfficientNetB4**, a state-of-the-art convolutional neural network, due to its:
- High accuracy on image classification tasks.
- Efficient computation and smaller model size.

---

## Results

| Metric             | Value       |
|--------------------|-------------|
| Validation Accuracy| **96.12%** |
| Loss               | Low         |

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- TensorFlow
- NumPy
- Matplotlib
- Pandas

### Setup
Clone the repository:
```bash
git clone https://github.com/kiranbirajdar199/CapstoneProject.git
cd CapstoneProject

