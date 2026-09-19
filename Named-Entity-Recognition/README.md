# Named Entity Recognition (NER)

## Overview

This assignment focuses on building a neural network for Named Entity Recognition (NER) using TensorFlow. NER is an information extraction task that identifies and classifies named entities in text, such as people, organizations, locations, and time expressions.

The notebook covers text and label encoding, padding sequences, building an LSTM-based model, training and evaluating the model, and testing predictions on a custom sentence.

## Objectives

* Design, train, and test a neural network for sequence labeling.
* Explore and preprocess a labeled NER dataset.
* Encode sentences and their corresponding entity labels.
* Apply padding to ensure consistent sequence lengths.
* Understand how recurrent neural networks process sequential inputs.
* Implement an LSTM-based model using TensorFlow.
* Evaluate model accuracy.
* Test the trained model on a custom sentence.

## Methodology

### 1. Data Exploration

* Import and inspect the labeled dataset.
* Examine sentences and their associated entity tags.

### 2. Text and Label Encoding

* Convert words in sentences into numerical representations.
* Encode named entity labels.
* Build a label vectorizer for converting predictions back into labels.

### 3. Sequence Padding

* Pad sentences and labels to consistent lengths.
* Understand how padding supports batch processing in recurrent neural networks.
* Use masked loss and metrics to account for padded positions during training and evaluation.

### 4. Model Development

* Design a neural network using TensorFlow.
* Use an LSTM layer to learn sequential patterns in text.
* Produce predictions for each token in an input sentence.

### 5. Training and Evaluation

* Train the model on the prepared dataset.
* Evaluate its performance using accuracy and the assignment's evaluation procedure.

### 6. Custom Sentence Prediction

* Test the trained NER model on a sentence of your choice.
* Examine the predicted labels for each word.

## Key Concepts

* Named Entity Recognition (NER)
* Sequence labeling
* Text and label encoding
* Word padding
* Recurrent Neural Networks (RNNs)
* Long Short-Term Memory (LSTM)
* Masked loss and metrics
* Token-level classification
* Model training and evaluation

## Technologies

* Python
* TensorFlow
* NumPy
* Jupyter Notebook

## Learning Outcomes

By completing this assignment, I practiced preparing sequential text data, encoding token-level labels, handling padded sequences, building an LSTM-based NER model, and evaluating predictions on both dataset examples and a custom sentence.

## Notebook

`Named_Entity_Recognition.ipynb`

## Course Information

* **Course:** Natural Language Processing with Sequence Models
* **Specialization:** Natural Language Processing
* **Platform:** Coursera
* **Assignment:** Named Entity Recognition (NER)

## Purpose

This project is part of my NLP learning portfolio, documenting practical experience with neural sequence models and token-level information extraction.
