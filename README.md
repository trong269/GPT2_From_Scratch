# GPT-2 From Scratch

This project demonstrates how to build, train, and evaluation a GPT-2 model from scratch using PyTorch. The implementation includes data preprocessing, model architecture, training loop, and inference.

## 📌 Features
- Built GPT-2 architecture from scratch
- Tokenization and dataset preparation
- Training from scratch using custom datasets
- model testing and evaluation

## 🏛 Architecture
GPT-2 is a Transformer-based language model designed for text generation. Key components include:
- **Positional Embedding**
- **Multi-head Self-Attention**: Captures contextual dependencies across words.
- **Feedforward Layers**: Applies non-linear transformations.
- **Layer Normalization & Residual Connections**: Stabilizes training and improves convergence.
- **Causal Masking**: Ensures autoregressive text generation.
- **Transformer Decoder Block**

The model follows a stacked Transformer decoder architecture with multiple attention heads, making it highly effective for generating coherent text sequences.

## 🛠 Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/trong269/GPT2_From_Scratch.git
```
