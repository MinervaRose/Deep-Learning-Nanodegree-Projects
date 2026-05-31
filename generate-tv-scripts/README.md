<div align="center">

# 📺 Generate TV Scripts with Recurrent Neural Networks

### Natural Language Processing • Sequence Modelling • Neural Text Generation

![Python](https://img.shields.io/badge/Python-NLP-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-RNNs-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Text%20Generation-success?style=for-the-badge)
![RNN](https://img.shields.io/badge/Architecture-RNN-blue?style=for-the-badge)
![LSTM](https://img.shields.io/badge/Architecture-LSTM-purple?style=for-the-badge)
![Sequence Models](https://img.shields.io/badge/AI-Sequence%20Models-orange?style=for-the-badge)
![Udacity](https://img.shields.io/badge/Udacity-Deep%20Learning%20Nanodegree-02B3E4?style=for-the-badge)

</div>

---

## Overview

This project explores neural text generation using recurrent neural networks.

The objective is to train a language model capable of generating new television dialogue after learning patterns from an existing TV script dataset.

While the generated text is not intended to rival modern large language models, the project provides hands-on experience with sequence modelling, language generation, and the foundations of neural language processing.

In hindsight, projects like this represent an important stage in the evolution of AI language systems before the widespread adoption of transformer architectures and modern LLMs.

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Recurrent Neural Networks (RNNs)
* Long Short-Term Memory Networks (LSTMs)
* Sequence Modelling
* Language Generation
* Text Preprocessing
* Tokenization
* Deep Learning with PyTorch
* Neural Language Models

---

## Project Objective

The goal is to train a neural network capable of generating new dialogue in the style of an existing television script.

The workflow follows a typical language modelling pipeline:

```text id="fzl6rd"
Raw Script
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
Vocabulary Construction
      ↓
Sequence Training
      ↓
RNN / LSTM Model
      ↓
Generated Dialogue
```

The model learns statistical patterns in language and attempts to generate plausible continuations of text based on those learned patterns.

---

## Sequence Modelling

Unlike image classification tasks, language generation requires the model to understand order and context.

For example:

```text id="g6uxkc"
The dog chased the...
```

requires different predictions than:

```text id="7t9eih"
The cat slept on the...
```

The network therefore learns relationships between words and sequences rather than treating each token independently.

---

## Deep Learning Approach

The project uses recurrent neural network architectures designed for sequential data.

### Concepts Explored

* Sequential Learning
* Hidden State Representations
* Word Embeddings
* Language Modelling
* Text Generation

These ideas formed the foundation of many language-generation systems that predated transformer-based architectures.

---

## Historical Perspective

One interesting aspect of this project is that it highlights how far language generation has evolved.

At the time, recurrent neural networks represented a major step forward in natural language generation.

Today, transformer-based models and large language models achieve dramatically higher levels of coherence and contextual understanding.

This project therefore provides a useful historical snapshot of neural language modelling before the emergence of modern generative AI systems.

---

## Results

The trained model successfully learned local language patterns and generated synthetic dialogue inspired by the training corpus.

The generated text demonstrates:

* Learned vocabulary usage
* Basic sentence structure
* Statistical language modelling
* Sequence prediction

Although the outputs are often imperfect and sometimes nonsensical, they illustrate the fundamental principles underlying neural text generation.

---

## Repository Contents

| File                            | Purpose                              |
| ------------------------------- | ------------------------------------ |
| dlnd_tv_script_generation.ipynb | Main project notebook                |
| report.html                     | HTML export of the completed project |
| problem_unittests.py            | Project validation tests             |

---

## Why This Project Matters

This project explores one of the most important ideas in artificial intelligence:

```text id="5n4x9h"
Prediction
      ↓
Sequence Prediction
      ↓
Language Generation
      ↓
Modern LLMs
```

The project therefore serves as an early introduction to neural language modelling and the broader family of technologies that eventually led to today's large language models.

While modern systems have largely moved beyond recurrent architectures, understanding these earlier approaches provides valuable insight into the evolution of generative AI.

---

## Historical Context

This project was completed as part of the **Udacity Deep Learning Nanodegree**.

It represents an early exploration of neural language generation and sequence modelling, helping establish foundational knowledge in NLP, language modelling, and generative AI systems.
