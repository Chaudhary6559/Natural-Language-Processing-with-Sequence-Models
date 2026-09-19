# Natural Language Processing with Sequence Models

This repository contains my coursework and practical assignments from **Natural Language Processing with Sequence Models**, the third course in the **Natural Language Processing Specialization** on Coursera.

The course focuses on neural network architectures for processing sequential data and applying them to natural language processing tasks. The assignments cover recurrent neural networks, GRUs, LSTMs, named entity recognition, Siamese networks, semantic similarity, and neural text generation.

## Assignments

| Assignment                                              | Description                                                                                                                      |
| ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [Deep N-grams](./Deep-N-grams/)                         | Build a GRU-based character-level language model for next-character prediction, evaluate it using perplexity, and generate text. |
| [Named Entity Recognition](./Named-Entity-Recognition/) | Build an LSTM-based sequence-labeling model to identify and classify named entities in text.                                     |
| [Question Duplicates](./Question-Duplicates/)           | Build a Siamese network to determine whether two questions are semantically similar or duplicates.                               |

## Course Topics

### 1. Deep N-grams

Explores neural language modeling and text generation using recurrent architectures.

**Key concepts:**

* Recurrent Neural Networks (RNNs)
* Gated Recurrent Units (GRUs)
* Character-level language modeling
* Character embeddings
* TensorFlow datasets
* Next-character prediction
* Perplexity
* Text generation

### 2. Named Entity Recognition

Develops a neural sequence-labeling model for identifying named entities in text.

**Key concepts:**

* Named Entity Recognition (NER)
* Sequence labeling
* Text and label encoding
* Word padding
* Masked loss and metrics
* Long Short-Term Memory (LSTM)
* Token-level classification
* Model evaluation

### 3. Question Duplicates

Uses Siamese neural networks to learn representations of questions and identify semantically similar question pairs.

**Key concepts:**

* Siamese networks
* Shared network parameters
* Word embeddings
* LSTM representations
* Triplet loss
* Hard negative mining
* Cosine similarity
* Semantic similarity
* Duplicate question detection

## Learning Progression

```text id="r8yq2p"
Neural Language Modeling
        │
        ▼
Deep N-grams
(RNNs / GRUs / Text Generation)
        │
        ▼
Sequence Labeling
        │
        ▼
Named Entity Recognition
(LSTMs / Token Classification)
        │
        ▼
Semantic Similarity
        │
        ▼
Question Duplicates
(Siamese Networks / Triplet Loss)
```

The assignments progressively move from **neural language modeling and sequence generation** to **sequence labeling** and finally to **learning semantic representations for sentence similarity**.

## Technologies

* Python
* TensorFlow
* NumPy
* Jupyter Notebook

## Skills Demonstrated

* Neural network design for NLP
* Recurrent neural networks
* GRU and LSTM architectures
* Text preprocessing and numerical encoding
* Sequence padding
* TensorFlow model development
* Neural language modeling
* Text generation
* Named entity recognition
* Siamese network architectures
* Sentence/question representations
* Triplet-loss-based learning
* Hard negative mining
* Cosine similarity
* Model training and evaluation

## Repository Structure

```text id="z9tq4m"
Natural-Language-Processing-with-Sequence-Models/
│
├── Deep-N-grams/
│   ├── Deep_N_grams.ipynb
│   └── README.md
│
├── Named-Entity-Recognition/
│   ├── Named_Entity_Recognition.ipynb
│   └── README.md
│
├── Question-Duplicates/
│   ├── Question_Duplicates.ipynb
│   └── README.md
│
└── README.md
```

## Learning Outcomes

Through these projects, I developed practical experience with neural sequence models and their applications in natural language processing.

The assignments provided hands-on practice with:

* Processing and representing sequential text data.
* Building neural language models.
* Training GRU and LSTM networks with TensorFlow.
* Generating text using trained neural models.
* Performing token-level classification with NER.
* Learning semantic representations of questions.
* Measuring similarity between learned vector representations.
* Applying Siamese architectures, triplet loss, and hard negative mining.

## Course Information

* **Course:** Natural Language Processing with Sequence Models
* **Specialization:** Natural Language Processing
* **Platform:** Coursera
* **Course:** 3 of the NLP Specialization

## Purpose

This repository is part of my NLP learning portfolio and documents my hands-on work with **deep learning and sequence modeling for natural language processing**.

It demonstrates the progression from recurrent language models to more advanced architectures for information extraction and semantic similarity.
