# Question Duplicates

## Overview

This assignment explores Siamese neural networks for identifying semantically similar or duplicate questions. Using the Quora question-pair dataset, the model processes two questions through shared neural network components and compares their learned representations.

The notebook covers question encoding, Siamese network architecture, triplet loss, hard negative mining, model training, cosine similarity, evaluation, and predictions on custom questions.

## Objectives

* Understand Siamese network architectures for natural language processing.
* Prepare and encode question-pair data.
* Implement a model that learns representations of questions.
* Understand and apply triplet loss.
* Explore hard negative mining.
* Compare question representations using cosine similarity.
* Train and evaluate a question similarity model.
* Test predictions using custom questions.

## Dataset

The assignment uses the **Quora question-pair dataset**, which contains pairs of questions labeled according to whether they are duplicates.

## Methodology

### 1. Data Preparation

* Load and explore the question-pair dataset.
* Build a vocabulary and encode questions as tensors.
* Generate batches of question examples for training.

### 2. Siamese Network Architecture

* Process each question through a shared neural network.
* Use embeddings and LSTM layers to create question representations.
* Compare the resulting vectors to estimate semantic similarity.

### 3. Triplet Loss and Hard Negative Mining

* Learn how triplet loss encourages similar questions to have closer representations than dissimilar questions.
* Apply hard negative mining to identify challenging negative examples during training.

### 4. Model Training

* Train the Siamese network using generated question batches.
* Learn vector representations that help distinguish duplicate from non-duplicate questions.

### 5. Evaluation and Classification

* Evaluate the trained model.
* Use cosine similarity between question vectors to classify question pairs.

### 6. Custom Question Testing

* Test the model with user-provided question pairs.
* Examine its predictions for whether the questions are duplicates.

## Key Concepts

* Siamese neural networks
* Question-pair similarity
* Shared neural network weights
* Word embeddings
* Long Short-Term Memory (LSTM)
* Triplet loss
* Hard negative mining
* Cosine similarity
* Semantic representations
* Text classification

## Technologies

* Python
* TensorFlow
* NumPy
* Jupyter Notebook

## Learning Outcomes

By completing this assignment, I practiced building a Siamese architecture, learning text representations with LSTMs, applying triplet loss and hard negative mining, and comparing question embeddings using cosine similarity.

## Notebook

`Question_Duplicates.ipynb`

## Course Information

* **Course:** Natural Language Processing with Sequence Models
* **Specialization:** Natural Language Processing
* **Platform:** Coursera
* **Assignment:** Question Duplicates

## Purpose

This project is part of my NLP learning portfolio, documenting practical experience with neural architectures for semantic similarity and duplicate-question detection.
