# lab 8- Diffusion Models

# Problem Statement

The goal of this project is to classify movie reviews as positive or negative sentiment using a neural network. Traditional models struggle with sequential text, so we use a Recurrent Neural Network (RNN) to capture word order and context.

# Approach

We solve this using a SimpleRNN-based deep learning model:

- Dataset: IMDb movie review dataset (pre-tokenized)
- Preprocessing:
-  Limit vocabulary size (e.g., 10,000 words)
-  Pad/truncate reviews to fixed length (e.g., 500 words)
- Model Architecture:
- Embedding Layer (word vector representation)
- SimpleRNN layer (captures sequential dependencies)
- Dense layer with sigmoid activation for binary classification

- Loss Function: Binary Crossentropy
- Optimizer: Adam

# Results
- Training Accuracy: ~80% (varies by run)
- Test Accuracy: ~70–75%
Observations:
- Model improves over epochs but saturates due to vanishing gradients
- Performance is lower than LSTM-based models
  
# Key Findings
- RNNs capture sequence information better than basic dense networks
- However, SimpleRNN suffers from vanishing gradient problems
- Longer reviews reduce performance due to memory limitations in RNNs

# Technologies 
- Python 3.x
- TensorFlow / Keras
- NumPy
- IMDb dataset (Keras built-in)

# How to Run
- Open in Google Colab OR Jupyter Notebook
- Run all cells sequentially
