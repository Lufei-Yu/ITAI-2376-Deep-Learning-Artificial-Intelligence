# README for Lab 3 – Convolutional Neural Networks

## Problem Statement
This lab focuses on improving neural network training through optimization algorithms and regularization techniques to reduce overfitting and improve generalization.

## Approach
- Compared optimizers: SGD, Adam, RMSProp.
- Implemented regularization methods:
  - L2 weight decay
  - Dropout layers
  - Early stopping
- Plotted training vs. validation loss to analyze model behavior.

## Results
- Dropout reduced overfitting and improved validation accuracy.
- Early stopping prevented unnecessary training and improved generalization.

## Key Findings
- Regularization is essential for preventing overfitting.
- Optimizer choice affects both speed and stability of training.
- Visualization of loss curves helps diagnose model issues.

## Technologies Used  
- PyTorch or TensorFlow  
- Matplotlib / Seaborn  
- Jupyter Notebook

## How to Run
1. Launch the notebook in Jupyter or Google Colab.
2. Install dependencies:
   ```bash
   pip install torch torchvision matplotlib
