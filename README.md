# RNN-QA: Simple RNN-based Question Answering System
---

## Project Overview
**RNN-QA** is a simple **question-answering system** implemented using a **Recurrent Neural Network (RNN)** in PyTorch.  
It can answer questions from a small predefined dataset by learning sequences of words and predicting answers.

Key concepts demonstrated:
- Tokenization and vocabulary building
- Sequence modeling using RNN
- Word embeddings
- Training and prediction loops in PyTorch

---

## Features
- Builds numerical vocabulary from questions and answers
- Uses embeddings and RNN to model question sequences
- Predicts answers from vocabulary using a softmax classifier
- Implements confidence threshold for unknown questions
- Training loop with loss tracking

---

## Technologies Used
- Python 3.x
- PyTorch
- Pandas
- Matplotlib (optional, for visualizations)
- Jupyter Notebook / Google Colab

---

## Dataset
- **100 Unique QA Dataset** (`100_Unique_QA_Dataset.csv`)
- Each row contains:
  - `question`: The question string
  - `answer`: The corresponding answer string
- Vocabulary is automatically built from all questions and answers.

---
