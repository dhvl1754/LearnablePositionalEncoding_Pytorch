# LearnablePositionalEncoding_Pytorch

This repository contains an implementation of Learnable Positional Encoding using PyTorch, integrated into a simple Transformer-based model. The project demonstrates how learnable positional encodings can be used to incorporate positional information into Transformer models. A synthetic dummy dataset is used for training and evaluation.

## Parameters Used

- **`vocab_size`**: Size of the vocabulary, set to 50, representing the total number of unique tokens.
- **`d_model`**: Embedding size, set to 32, defining the dimensionality of token representations.
- **`max_len`**: Maximum sequence length, set to 60, indicating the longest sequence the model can handle.
- **`seq_length`**: Sequence length, set to 10, specifying the number of tokens in each input sequence.
- **`batch_size`**: Batch size, set to 32, determining the number of sequences processed in one batch.
- **`num_heads`**: Number of attention heads, set to 4, enabling multi-head attention to focus on different sequence patterns.
- **`num_layers`**: Number of transformer layers, set to 2, providing the depth of the encoder for feature extraction.
- **`dropout`**: Dropout rate, set to 0.1, used for regularization to prevent overfitting.
- **`epochs`**: Number of training epochs, set to 10, indicating the number of complete passes through the dataset.
- **`learning_rate`**: Learning rate, set to 0.001, controlling the step size for optimizer updates.

