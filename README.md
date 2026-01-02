# Sentiment-Analysis-using-LSTM-AWD-LSTM-ULMFiT-BERT-
This project compares LSTM, AWD-LSTM (ULMFiT), and BERT models for sentiment analysis on IMDb reviews to study the impact of transfer learning and transformer-based architectures on NLP performance.
The project evaluates:

A Custom LSTM model trained from scratch

A Pretrained AWD-LSTM (ULMFiT) model

A Transformer-based BERT model

The comparison highlights the effectiveness of transfer learning and contextual understanding in NLP.

# Objectives

Build and train an LSTM model from scratch

Fine-tune a pretrained AWD-LSTM model

Implement a transformer-based BERT model

Compare all models using identical evaluation metrics

Analyze performance, convergence, and computational cost.

# Models Implemented
🔹 Custom LSTM (PyTorch)

Trained from scratch

Learns task-specific features

Slower convergence

🔹 AWD-LSTM (ULMFiT)

Pretrained language model

Fine-tuned on IMDb dataset

Faster convergence and higher accuracy

🔹 BERT (Transformer Model)

bert-base-uncased

WordPiece tokenization

Best contextual understanding and accuracy

Higher computational cost

# Dataset:

Dataset: IMDb Movie Reviews

Source: Stanford AI Lab / HuggingFace

Size: 50,000 labeled reviews

Labels: Positive / Negative

# Tech Stack

Language: Python

Frameworks: PyTorch, FastAI

Libraries: HuggingFace Transformers, NumPy, Pandas

Domain: Natural Language Processing, Deep Learning
