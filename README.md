# Neural-Decoder
NeuralDecoder is a neural-network-based decoder for a Hamming (7,4) system. It takes 7 noisy received bits as input and predicts the original 4-bit message from 16 possible outputs. It uses Eb/N0 to model noise and trains a classifier with Adam optimizer and CrossEntropyLoss to learn error correction from noisy codewords.

# Neural Decoder for Hamming (7,4)

This project implements a NeuralDecoder using a neural network for decoding Hamming (7,4) coded messages in a noisy communication channel.

## Overview
The model takes 7-bit noisy received codewords and predicts the original 4-bit message (16 possible classes). Noise is simulated using Eb/N0, and the network learns to correct errors automatically.

## How to Run (Google Colab)
1. Open the `.ipynb` file in Google Colab.
2. Click **Runtime → Run all**.
3. The notebook will install dependencies (if needed), train the model, and show results.

## Requirements
- Python 3
- PyTorch
- NumPy
- Google Colab (recommended)

## Features
- Hamming (7,4) encoding/decoding
- Noise simulation using Eb/N0
- Neural network classifier
- Training with Adam optimizer and CrossEntropyLoss

## Output
The model predicts the original 4-bit message from noisy inputs and improves decoding accuracy.

## Author
Your Name
