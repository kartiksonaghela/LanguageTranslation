# Language Translation using Transformer Architecture

## Overview

This repository contains a language translation model built from scratch using the Transformer architecture in PyTorch. The model is designed to translate text from English to another target language.

## Features

- Built using the Transformer architecture as described in the paper ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762)
- Implements multi-head self-attention and positional encoding
- Trained using PyTorch
- Capable of translating English text to a target language

## Dataset

The dataset used for training was collected from Kaggle and model was trained on 200,000 sentences. 

## Configuration

The model's configuration can be adjusted in the `config.json` file. Key parameters include:

- `num_layers`: Number of layers in the encoder and decoder
- `num_heads`: Number of attention heads
- `hidden_dim`: Dimension of the hidden layers
- `dropout`: Dropout rate
- `learning_rate`: Learning rate for the optimizer
