# Multi-Label Emotion Classification in Text Using XLM-Roberta

This repository implements a multi-label emotion classification model using the XLM-Roberta transformer model. It handles text data from multiple languages, processes and augments it, balances the dataset, and performs model training and evaluation.

## Overview

The project aims to classify emotions in text data across multiple languages. The classification process involves several steps including:

1. **Text Preprocessing**: Clean and normalize text by removing unwanted characters and stopwords, then applying lemmatization.
2. **Text Augmentation**: Use synonym replacement to generate synthetic data and improve the model's generalization.
3. **Data Resampling**: Handle class imbalance by oversampling minority classes.
4. **Model Training**: Train a multi-label classification model using XLM-Roberta.
5. **Evaluation**: Evaluate model performance using F1-score and accuracy.

## Requirements

- Python 3.x
- PyTorch
- Transformers library
- Scikit-learn
- NLTK
- Matplotlib, Seaborn
- Pandas
- NumPy

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Emotion-Classification.git
   cd Emotion-Classification
