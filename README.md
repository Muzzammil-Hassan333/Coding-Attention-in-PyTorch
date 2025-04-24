🎯 Coding Attention in PyTorch
This repository provides a beginner-friendly, hands-on implementation of Attention and Multi-Head Attention mechanisms using PyTorch — the building blocks behind powerful models like Transformers, BERT, and GPT.

📌 What You’ll Learn
The mechanics of scaled dot-product attention from scratch.

The difference between Self-Attention and Encoder-Decoder Attention.

How Multi-Head Attention works and how to implement it with modular PyTorch components.

How to verify attention computations manually using interpretable 2D input vectors.

🧠 Components
Attention: A fully-functional PyTorch module that computes attention using query, key, and value encodings.

MultiHeadAttention: A simplified multi-head attention module that concatenates outputs from multiple independent attention heads.

Includes usage demos for both single-head and multi-head setups, using synthetic data for clarity.

🧱 Key Features
Intuitive tensor shapes and manual softmax masking.

Scaled dot-product similarity for stability and performance.

Easily extendable for more heads or larger embedding sizes (d_model).

Simple torch-based implementation with no external dependencies beyond PyTorch.

🎯 Ideal For:
Machine learning students and practitioners curious about attention internals.

Anyone studying Transformers, NLP, or deep learning model architectures.

Developers seeking to build attention-based layers from the ground up.
