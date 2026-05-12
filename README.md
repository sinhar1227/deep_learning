# Deep Learning Repository

A comprehensive deep learning project exploring fundamental concepts and advanced architectures in neural networks.

## Project Overview

This repository contains implementations and explanations of key deep learning concepts, from basic activation functions to complex transformer architectures. It's designed for learning, experimentation, and reference.

## Project Structure

```
deep_learning/
├── main.py                          # Main entry point
├── pyproject.toml                   # Project configuration
├── README.md                        # This file
├── Activation Function/
│   └── activation_function.ipynb    # Activation functions exploration and implementation
└── Transformer/
    ├── bert.ipynb                   # BERT (Bidirectional Encoder Representations from Transformers)
    └── transformer_from_scratch_code.ipynb  # Transformer architecture from scratch
```

## Contents

### Activation Functions

Explore various activation functions used in neural networks:

- Understanding different activation functions
- Implementation details
- Performance comparisons
- Use cases and best practices

**File:** `Activation Function/activation_function.ipynb`

### Transformers

Deep dive into transformer architecture:

- **BERT**: Pre-trained bidirectional transformer model
- **Transformer from Scratch**: Complete implementation of the transformer architecture

**Files:**

- `Transformer/bert.ipynb`
- `Transformer/transformer_from_scratch_code.ipynb`

## Requirements

- Python >= 3.12
- Dependencies:
  - `numpy >= 2.4.4` - Numerical computing
  - `matplotlib >= 3.10.9` - Data visualization

## Installation

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install -e .
   ```

## Usage

Run the main script:

```bash
python main.py
```

For interactive exploration, open the Jupyter notebooks:

- `Activation Function/activation_function.ipynb`
- `Transformer/bert.ipynb`
- `Transformer/transformer_from_scratch_code.ipynb`

## Getting Started

1. Start with `Activation Function/activation_function.ipynb` to understand the basics
2. Progress to `Transformer/transformer_from_scratch_code.ipynb` for architecture fundamentals
3. Explore `Transformer/bert.ipynb` for practical pre-trained model applications

## Technologies & Concepts

- **Deep Learning**: Neural network architectures and training
- **Transformers**: Self-attention mechanisms and modern NLP models
- **Python**: Primary programming language
- **Jupyter Notebooks**: Interactive learning and experimentation
- **NumPy**: Numerical computations
- **Matplotlib**: Visualization

## License

This is a personal learning and research repository.

## Notes

This repository serves as a learning resource for deep learning concepts. The implementations focus on understanding over production optimization.
