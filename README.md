# Quantum-Classical Hybrid Deep Learning for COVID-19 Detection

## Overview

This project implements a Hybrid Quantum-Classical Deep Learning framework for COVID-19 chest X-ray image classification using PyTorch and PennyLane.

The system combines:

* Convolutional Neural Networks (CNNs)
* Quantum Machine Learning (QML)
* Noise robustness testing
* Medical image preprocessing
* Hybrid quantum-classical architecture

The project was developed and tested using Google Colab.

---

# Project Objectives

The main objectives of this project are:

* Detect COVID-19 from chest X-ray images
* Compare classical CNN and hybrid quantum-classical models
* Evaluate robustness under noisy image conditions
* Explore applications of Quantum Machine Learning in healthcare
* Build a research-oriented implementation suitable for IEEE-style projects

---

# Technologies Used

| Technology   | Purpose                             |
| ------------ | ----------------------------------- |
| Python       | Programming Language                |
| PyTorch      | Deep Learning Framework             |
| PennyLane    | Quantum Machine Learning            |
| Google Colab | Cloud-based Development Environment |
| Matplotlib   | Data Visualization                  |
| Pandas       | Data Processing                     |
| Scikit-learn | Dataset Splitting                   |
| PIL          | Image Processing                    |

---

# Dataset Information

## Dataset Name

COVID Chest X-Ray Dataset

## Dataset Source

[https://github.com/ieee8023/covid-chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset)

## Dataset Description

The dataset contains chest X-ray images collected for COVID-19 detection research and medical imaging analysis.

## Important Note

The dataset is not uploaded to this repository because of GitHub file size limitations.

---

# Dataset Download

Run the following command in Google Colab to download the dataset:

```python
!wget https://github.com/ieee8023/covid-chestxray-dataset/archive/refs/heads/master.zip
```

Extract the dataset:

```python
!unzip master.zip
```

---

# Project Structure

```text
quantum-covid-detection/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── dataset_info.txt
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/quantum-covid-detection.git
```

## Move into Project Directory

```bash
cd quantum-covid-detection
```

## Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# Required Libraries

```text
torch
torchvision
pennylane
pandas
numpy
matplotlib
scikit-learn
Pillow
```

---

# Data Preprocessing

The following preprocessing operations were performed:

* Image resizing
* Tensor conversion
* Label generation
* Dataset validation
* Noise augmentation
* Training-validation split

Image size used:

```text
128 × 128
```

---

# Classical CNN Architecture

The CNN model contains:

* Convolution layers
* ReLU activation
* MaxPooling layers
* Fully connected layers
* Binary classification output

The CNN extracts spatial image features from chest X-ray images.

---

# Quantum Circuit

The quantum circuit was implemented using PennyLane.

## Quantum Components

* Angle Embedding
* Basic Entangler Layers
* Pauli-Z Measurements
* 4 Qubits

The quantum layer processes features extracted from the CNN model.

---

# Hybrid Quantum-Classical Model

The hybrid architecture combines:

1. Classical CNN Feature Extraction
2. Quantum Feature Processing
3. Final Classification Layer

This approach explores the integration of quantum computing with deep learning for medical image classification.

---

# Noise Robustness Testing

Noise augmentation was applied to evaluate model robustness.

Noise levels tested:

| Noise Level | Purpose        |
| ----------- | -------------- |
| 0.1         | Mild Noise     |
| 0.2         | Moderate Noise |
| 0.5         | Strong Noise   |

Gaussian noise was added using PyTorch tensor operations.

---

# Training Configuration

| Parameter        | Value              |
| ---------------- | ------------------ |
| Optimizer        | Adam               |
| Learning Rate    | 0.001              |
| Loss Function    | CrossEntropyLoss   |
| Epochs           | 5                  |
| Batch Processing | PyTorch DataLoader |

---

# Results

The project evaluates:

* Validation accuracy
* Noisy image accuracy
* Hybrid model performance
* CNN robustness

Example outputs:

```text
Validation Accuracy: XX.XX%
Hybrid Model - Noisy Accuracy: XX.XX%
```

---

# Figures

Store generated graphs and sample outputs inside the `figures/` folder.

Example figures:

* Sample chest X-ray image
* Training loss graph
* Accuracy comparison chart
* Noise robustness evaluation graph

---

# Example Google Colab Workflow

1. Download Dataset
2. Load Metadata
3. Preprocess Images
4. Build CNN Model
5. Build Quantum Circuit
6. Train Hybrid Model
7. Evaluate Accuracy
8. Test Noise Robustness
9. Save Results

---

# Future Improvements

Possible future enhancements:

* Larger medical imaging datasets
* More advanced quantum circuits
* Transfer learning models
* Real-time healthcare deployment
* Explainable AI integration
* Quantum hardware implementation

---

# Research Applications

This project can be useful for:

* IEEE Research Papers
* Quantum Machine Learning Research
* Healthcare AI Applications
* PhD Applications
* MEXT Scholarship Projects
* AI Research Portfolios

---

# Author

Saichandu Kundarapu

PhD Research Interest:
Quantum Machine Learning and Artificial Intelligence in Healthcare

---

# License

This project is intended for educational and research purposes.

Please follow the original dataset licensing terms provided by the dataset authors.

---

# Acknowledgements

Special thanks to:

* COVID Chest X-Ray Dataset Contributors
* PyTorch Community
* PennyLane Community
* Open Source Research Community

---

# GitHub Repository

Replace the repository link below with your actual GitHub repository URL:

```text
https://github.com/your-username/quantum-covid-detection
```
