# Deep Learning Model Optimization for Image Classification Using Collaborative Optimization Techniques 

## Description
![Compression Pipeline](https://github.com/FYP-19/Model/assets/73242822/d7cedec5-d372-487d-82b9-e9d09a2c9230)

This repository showcases a comprehensive approach to model optimization using sparsity, sparsity-preserving clustering, and quantization-aware training (PCQAT) utlizing TensorFlow Model Optimization Toolkit (TFMOT). It provides a step-by-step guide and code implementation to:

- Train a MobileNet V2 model for your custom animal camera trap dataset.
- Prune the trained model and evaluate its accuracy and sparsity preservation.
- Apply sparsity-preserving clustering to maintain sparsity.
- Implement PCQAT for combined sparsity and cluster preservation with quantization.
- Generate a TFLite model for deployment and compare its size reduction.
- Analyze the trade-offs between model size/inference latency and accuracy throughout the optimization process.

## Key Features

- **Practical Example**: Illustrates the entire model optimization journey on a real-world dataset.
- **Step-by-Step Guide**: Clear instructions for each optimization stage.
- **Code Implementation**: Provides ready-to-run code for replication.
- **Comparative Analysis**: Evaluates model size reduction and accuracy impact.

## Target Audience

- Machine learning practitioners seeking to optimize their models for deployment.
- TensorFlow users interested in leveraging TFMOT for efficient model training and inference.

## Installation

1. Set up a virtual environment (recommended).
2. Install required dependencies using pip:

```bash
pip install -q tensorflow-model-optimization



