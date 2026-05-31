<div align="center">

# 😊 Deploying a Sentiment Analysis Model

### Natural Language Processing • Deep Learning • Model Deployment

![Python](https://img.shields.io/badge/Python-Deep%20Learning-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-LSTM%20Classifier-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-4CAF50?style=for-the-badge)
![AWS SageMaker](https://img.shields.io/badge/AWS-SageMaker-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Deployment](https://img.shields.io/badge/AI-Deployment-9C27B0?style=for-the-badge)
![Udacity](https://img.shields.io/badge/Udacity-Deep%20Learning%20Nanodegree-02B3E4?style=for-the-badge)

</div>

---

## Overview

This project demonstrates the complete lifecycle of a Natural Language Processing (NLP) application, from data preparation and model training to cloud deployment.

Using a dataset of IMDb movie reviews, a Long Short-Term Memory (LSTM) neural network is trained to classify reviews as either **positive** or **negative** sentiment. The trained model is then deployed using **Amazon SageMaker**, allowing predictions to be generated through a hosted inference endpoint.

Unlike many machine learning projects that focus solely on model development, this project explores the practical challenges involved in deploying a trained model for real-world use.

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Sentiment Analysis
* Deep Learning with PyTorch
* Long Short-Term Memory Networks (LSTMs)
* Text Preprocessing
* Model Training
* Model Serialization
* Amazon SageMaker
* Cloud Deployment
* Inference Pipelines

---

## Project Objective

The objective is to build and deploy a sentiment analysis model capable of classifying movie reviews as positive or negative.

The project follows an end-to-end machine learning workflow:

```text
IMDb Reviews
      ↓
Text Preprocessing
      ↓
Vocabulary Construction
      ↓
LSTM Training
      ↓
Model Evaluation
      ↓
SageMaker Deployment
      ↓
Hosted Endpoint
      ↓
Sentiment Predictions
```

The final system demonstrates how a deep learning model can be trained locally and deployed as a cloud-based inference service.

---

## Dataset

The project uses the IMDb movie review dataset, a widely used benchmark for sentiment analysis.

Reviews are labelled as either:

* Positive
* Negative

The task is framed as a binary text classification problem.

---

## Model Architecture

The sentiment classifier is based on a Long Short-Term Memory (LSTM) neural network.

### Key Components

* Word Embeddings
* Sequence Processing
* LSTM Layers
* Fully Connected Classification Layer
* Binary Sentiment Prediction

LSTMs are particularly effective for sequential text data because they can learn contextual relationships between words appearing across a sentence or review.

---

## Deployment Workflow

One of the main objectives of this project is to demonstrate deployment rather than simply model training.

The workflow includes:

1. Data preparation and preprocessing
2. Training a PyTorch sentiment classifier
3. Packaging the trained model
4. Deploying the model using Amazon SageMaker
5. Serving predictions through a hosted endpoint

This transforms a trained machine learning model into a reusable service capable of processing new user inputs.

---

## Results

The trained model achieved approximately:

```text
Test Accuracy: 84.6%
```

The deployed endpoint successfully generated sentiment predictions for previously unseen movie reviews, demonstrating the complete training-to-deployment pipeline.

---

## Repository Contents

| File                    | Purpose                                                                                    |
| ----------------------- | ------------------------------------------------------------------------------------------ |
| SageMaker Project.ipynb | Complete project notebook including data preparation, training, evaluation, and deployment |
| SageMaker Project.html  | HTML export of the completed notebook                                                      |
| train.py                | SageMaker training script used to train the model                                          |
| predict.py              | Inference script used by the deployed endpoint                                             |

---

## Why This Project Matters

This project explores an important aspect of modern AI engineering: moving beyond experimentation and into deployment.

While many machine learning projects conclude once a model has been trained, real-world AI systems must also be:

* Deployable
* Reproducible
* Maintainable
* Accessible through inference services

The project therefore serves as an early example of integrating machine learning development with practical deployment workflows.

---

## Historical Context

This project was completed as part of the **Udacity Deep Learning Nanodegree**.

It represents an early exploration of cloud-based machine learning deployment and production-oriented AI workflows. Many of the concepts encountered here—including model packaging, inference pipelines, and deployment architectures—continue to underpin modern AI engineering practices.
