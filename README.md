# Fine-Tuning RoBERTa for Binary Sentiment Classification (IMDb) with LoRA

## Overview

This repository contains a Jupyter Notebook for fine-tuning a RoBERTa model using the IMDb dataset for binary sentiment classification. The model is optimized using the **LoRA** (Low-Rank Adaptation) fine-tuning technique, which reduces the number of trainable parameters, making fine-tuning more efficient.

## Features

- **LoRA Fine-Tuning:** Fine-tunes a pre-trained RoBERTa model using the LoRA technique for efficient training.
- **Sentiment Classification:** Predicts binary sentiment (positive or negative) on the IMDb dataset.
- **Data Preprocessing:** Tokenizes and preprocesses the IMDb dataset.
- **Evaluation:** Evaluates model performance using accuracy, precision, recall, and F1-score.

## Requirements

- Python 3.7+
- `transformers` library
- `datasets` library (for IMDb dataset)
- `pandas`
- `peft`
- `lora` (Low-Rank Adaptation package)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Barri-FZ2001/Fine-tuning-RoBerta-model-for-binary-sentiment-classification-using-LORA-fine-tuning-technique.git
   cd Fine-tuning-RoBerta-model-for-binary-sentiment-classification-using-LORA-fine-tuning-technique
