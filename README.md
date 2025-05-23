# OCTMNIST CNN Classification

This project implements a convolutional neural network (CNN) to classify OCT (Optical Coherence Tomography) images using the MedMNIST dataset. It focuses on robust model building, training, and evaluation for medical image classification tasks.

## 🩺 Dataset

- **Dataset:** `OCTMNIST` from [MedMNIST](https://medmnist.com/)
- **Classes:** 4 classes representing different retinal conditions
- **Source:** Automatically downloaded via `medmnist` package

## 🧠 Features

- Exploratory analysis of image statistics and class balance
- Preprocessing and normalization
- CNN model built with PyTorch
- Use of class weights to handle imbalance
- Learning rate scheduler and dropout for regularization
- Evaluation with accuracy, precision, recall, F1-score, and ROC-AUC

## 📊 Metrics Used

- Accuracy
- Confusion Matrix
- ROC Curve and AUC
- Precision, Recall, F1-Score (macro and weighted)

## 🚀 How to Run

1. Install required libraries:

```bash
pip install medmnist torch torchvision torchinfo scikit-learn matplotlib seaborn
