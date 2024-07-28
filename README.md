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

- `d_model`: 512,
- `batch_size`: 30,
- `ffn_hidden`: 2048,
- `num_heads`: 8,
- `drop_prob`: 0.1,
- `num_layers`: 1,
- `max_sequence_length`: 500,
- `vocab_size_hindi`: 119,  # Update based on your actual vocabulary size
- `vocab_size_english`: 71  # Update based on your actual vocabulary size
