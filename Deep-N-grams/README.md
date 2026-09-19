# Deep N-grams

## Overview

This assignment explores character-level text generation using Recurrent Neural Networks (RNNs). A Gated Recurrent Unit (GRU) language model learns sequential patterns in text and predicts what comes next, providing a foundation for applications such as predictive text and automated text generation.

The notebook covers data preprocessing, TensorFlow dataset creation, GRU model development, training, evaluation using perplexity, and generating text with the trained model.

## Objectives

* Convert text lines into numerical tensors.
* Build a vocabulary for character-level text processing.
* Prepare training and testing datasets using TensorFlow.
* Generate input-output sequences for next-character prediction.
* Define and train a GRU-based language model.
* Evaluate the model using log perplexity.
* Generate text using the trained model.

## Methodology

### 1. Data Preprocessing

* Load and inspect the text data.
* Create a character vocabulary.
* Convert text lines into tensors.
* Prepare data for training and testing.

### 2. Dataset Preparation

* Create a TensorFlow dataset.
* Generate input and target sequences.
* Prepare batches for model training.

### 3. GRU Language Model

* Build a neural language model using TensorFlow.
* Represent characters using embeddings.
* Process sequential information with a GRU layer.
* Use a linear output layer and log-softmax to produce next-character predictions.

### 4. Model Training

* Train the model on prepared text sequences.
* Learn patterns and dependencies between characters.

### 5. Evaluation

* Evaluate language-model performance using log perplexity.
* Use perplexity to assess how well the model predicts the next character.

### 6. Text Generation

* Use the trained model to generate text.
* Explore how sequential predictions can produce new character sequences.

## Key Concepts

* Recurrent Neural Networks (RNNs)
* Gated Recurrent Units (GRUs)
* Character-level language modeling
* Text preprocessing and vocabulary creation
* TensorFlow datasets
* Character embeddings
* Next-character prediction
* Log-softmax
* Perplexity
* Neural text generation

## Technologies

* Python
* TensorFlow
* NumPy
* Jupyter Notebook

## Learning Outcomes

By completing this assignment, I practiced preparing text for neural sequence models, building and training a GRU language model, evaluating predictions with perplexity, and generating text from a trained model.

## Notebook

`Deep_N_grams.ipynb`

## Course Information

* **Course:** Natural Language Processing with Sequence Models
* **Specialization:** Natural Language Processing
* **Course platform:** Coursera
* **Assignment:** Deep N-grams

## Purpose

This project is part of my NLP learning portfolio, documenting practical work with recurrent neural networks and neural language modeling.
