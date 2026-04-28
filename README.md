# 🔥 Neural Networks: Zero to Hero — My Work

> My implementations and explorations following **Andrej Karpathy's** [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) course.

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)

---

## 📌 Overview

This repository contains my hands-on work following Andrej Karpathy's legendary "Neural Networks: Zero to Hero" series — one of the best resources for building a deep, first-principles understanding of modern neural networks and language models.

The series starts from scratch (literally building autograd by hand) and builds up to training transformer-based language models. Each notebook here corresponds to a key lecture in the series, with my own implementations, notes, and experiments.

---

## 📂 Notebooks

| # | Notebook | Lecture Topic |
|---|----------|---------------|
| 1 | [`1.pytorch_neural_network_micrograd.ipynb`](1.pytorch_neural_network_micrograd.ipynb) | **Micrograd** — building a scalar-valued autograd engine and a neural net from scratch; understanding backpropagation at its core |
| 2 | [`2.pytorch_nn_language_model_makemore.ipynb`](2.pytorch_nn_language_model_makemore.ipynb) | **Makemore (Bigram)** — building a character-level bigram language model; learning about probability distributions and cross-entropy loss |
| 3 | [`3.pytorch_nn_MLP_language_model_makemore.ipynb`](3.pytorch_nn_MLP_language_model_makemore.ipynb) | **Makemore (MLP)** — implementing a multi-layer perceptron language model following Bengio et al. 2003; embeddings, hidden layers, and batched training |
| 4 | [`4.pytorch_nn_MLP2_language_model_makemore.ipynb`](4.pytorch_nn_MLP2_language_model_makemore.ipynb) | **Makemore (MLP deep dive)** — BatchNorm, weight initialisation, and diagnosing training issues; becoming a backprop ninja |
| 5 | [`5.pytorch_nn_backprop_ninja_language_model_makemore.ipynb`](5.pytorch_nn_backprop_ninja_language_model_makemore.ipynb) | **Backprop Ninja** — manually deriving and implementing all gradients without using PyTorch autograd; deep understanding of the backward pass |
| 6 | [`6.pytorch_nn_wavenet_makemore.ipynb`](6.pytorch_nn_wavenet_makemore.ipynb) | **WaveNet-style model** — building a deeper hierarchical character-level model inspired by DeepMind's WaveNet architecture |
| 7 | [`7.tokenizer.ipynb`](7.tokenizer.ipynb) | **Tokenisation** — building a BPE (Byte Pair Encoding) tokenizer from scratch; understanding how text is converted into tokens for LLMs |

---

## 🔑 Concepts Covered

- **Automatic differentiation** from first principles (micrograd)
- **Bigram and MLP language models** from scratch
- **Backpropagation** — manual derivations and intuitions
- **Batch Normalisation** and proper weight initialisation
- **WaveNet-style hierarchical architectures**
- **Byte Pair Encoding (BPE) tokenisation**
- Throughout: **PyTorch** idioms and best practices

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install torch jupyter matplotlib
```

### Run locally

```bash
git clone https://github.com/palash147/nn-zero-to-hero-work.git
cd nn-zero-to-hero-work
jupyter notebook
```

The notebooks are CPU-friendly for the most part. A GPU speeds up training but isn't required.

---

## 📚 Course Reference

| Resource | Link |
|----------|------|
| 🎥 YouTube Playlist | [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) |
| 👨‍🏫 Instructor | [Andrej Karpathy](https://karpathy.ai/) |
| 📖 Original micrograd repo | [karpathy/micrograd](https://github.com/karpathy/micrograd) |
| 📖 Original makemore repo | [karpathy/makemore](https://github.com/karpathy/makemore) |

---

## 💡 Why This Course?

This series is exceptional for anyone who wants to go beyond API calls and *truly understand* how neural networks and language models work. By building everything from scratch — autograd, optimizers, language models, tokenisers — you develop strong intuitions that make it much easier to reason about and debug modern AI systems.

---

## 🤝 Contributing

If you're also working through the series, feel free to open issues or PRs with fixes, improvements, or interesting experiments!

---

## 👤 Author

**Palash** · [GitHub](https://github.com/palash147) · [LinkedIn](https://www.linkedin.com/in/palash147/)
