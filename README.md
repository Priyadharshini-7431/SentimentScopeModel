# SentimentScope: Sentiment Analysis Using Transformers

# Project Overview

SentimentScope is a sentiment analysis project that uses a Transformer-based deep learning model to classify movie reviews as positive or negative. The project uses the IMDB movie review dataset to train and evaluate a custom Transformer architecture implemented using PyTorch.

# Objectives

- Understand sentiment analysis using Transformer architecture.
- Process and analyze the IMDB movie review dataset.
- Implement self-attention and multi-head attention mechanisms.
- Train a text classification model using PyTorch.
- Evaluate the model using test accuracy.

# Dataset

- Dataset: IMDB Movie Reviews
- Training samples: 25,000
- Testing samples: 25,000
- Classes: Positive and Negative

The training dataset is split into training and validation sets.

# Technologies Used

- Python
- PyTorch
- Hugging Face Transformers (tokenizer)
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

# Model Architecture

The project implements a custom Transformer-based classification model with the following components:

- Attention Head
- Multi-Head Attention
- Feed-Forward Network
- Transformer Blocks
- Token and Positional Embeddings
- Layer Normalization
- Mean Pooling
- Classification Layer

The model predicts whether a movie review expresses positive or negative sentiment.

# Project Workflow

1. Load and preprocess the IMDB dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Tokenize movie reviews.
4. Create training, validation, and testing DataLoaders.
5. Build the custom Transformer model.
6. Train the model using a classification loss function.
7. Evaluate the trained model on the test dataset.
8. Analyze the results and visualize model performance.

# Results

- Test Accuracy: 76.72%
- Task: Binary sentiment classification
- Output classes: Positive and Negative

The model achieved 76% test accuracy on the IMDB test dataset.

# How to Run

1. Open the project notebook in Google Colab.
2. Install the required Python libraries.
3. Download and extract the IMDB dataset.
4. Run the notebook cells in order.
5. Train the model and evaluate its test accuracy.

# Learning Outcomes

- Learned the fundamentals of Transformer architecture.
- Implemented attention mechanisms using PyTorch.
- Gained practical experience in NLP and sentiment classification.
- Learned how to train and evaluate a deep learning model.

