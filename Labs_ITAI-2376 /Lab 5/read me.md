# Lab 5-RNNs vs Transformers vs Vision Transformers

# Problem Statement
This lab focuses on modeling sequential data such as text or time‑series signals. The objective is to understand how RNN‑based architectures (RNN, LSTM, GRU) capture temporal dependencies and how they differ in performance.

# Approach
- Preprocessed a sequence dataset (e.g., text classification or time‑series forecasting).
- Implemented three architectures:
  - Vanilla RNN
  - LSTM
  - GRU
- Compared:
  - Hidden size
  - Sequence length
  - Training stability
  - Accuracy and loss curves
- Evaluated models using accuracy, loss, and confusion matrices (if classification).

# Results
- GRU performed similarly to LSTM but trained faster due to fewer parameters.
- Vanilla RNN struggled with long sequences due to vanishing gradients.
- Longer sequences improved context understanding but increased computation time.

# Key Findings
- LSTMs and GRUs are more effective than RNNs for long‑term dependencies.
- Proper tokenization and padding are essential for stable training.
- Sequence models are sensitive to hyperparameters such as hidden size and learning rate.
- GRUs offer a strong balance between performance and efficiency.

# Technologies Used
- PyTorch / TensorFlow  
- Tokenizers (NLTK, spaCy, or HuggingFace)  
- NumPy, Matplotlib  
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter or Google Colab.
