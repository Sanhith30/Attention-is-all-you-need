# Attention-is-all-you-need
Attention Is All You Need - Transformers Implementation from Scratch
This project is a PyTorch-based reimplementation of the original Transformer architecture proposed in Attention Is All You Need (Vaswani et al., 2017) - Link. It reconstructs the core building blocks - multi-head self-attention, positional encodings, and encoder-decoder architecture from first principles to offer interpretability and clarity.

Structure
transformer_from_scratch.py — Main script containing modular implementations of attention, feedforward layers, and positional embeddings.

Fully built using native PyTorch (nn.Module) without relying on high-level abstractions.

How to run
git clone https://github.com/sanhith30/attention-is-all-you-need
cd attention-is-all-you-need
python transformers_from_scratch.py
Requires: Python 3.8+, PyTorch 1.13+
