# README for Lab 3 – Convolutional Neural Networks (CNNs)

## Problem Statement
This lab introduces convolutional neural networks for image classification tasks. The goal is to understand how convolution, pooling, and deep architectures improve performance on visual data.

## Approach
- Built a CNN with convolution, pooling, and fully connected layers.
- Trained on an image dataset (e.g., CIFAR-10, MNIST, or custom dataset).
- Experimented with:
  - Kernel sizes
  - Number of filters
  - Network depth
- Evaluated performance using accuracy and confusion matrices.

## Results
- Deeper models improved accuracy but required more training time.
- The confusion matrix revealed common misclassifications.

## Key Findings
- CNNs outperform fully connected networks on image tasks.
- Kernel size and filter count strongly influence feature extraction.
- Data augmentation can significantly improve accuracy.

## Technologies Used
- PyTorch / TensorFlow / Keras  
- Matplotlib  
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter or Colab.
2. Install dependencies:
   ```bash
   pip install torch torchvision matplotlib
