# Sentiment Analysis Using RNN, LSTM, and Transformer Models

This project demonstrates how to perform sentiment analysis on the IMDB dataset using Recurrent Neural Networks (RNNs), Long Short-Term Memory networks (LSTMs), and Transformer models, all implemented from scratch using PyTorch.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architectures](#model-architectures)
- [Setup and Installation](#setup-and-installation)
- [Data Preprocessing](#data-preprocessing)
- [Training the Models](#training-the-models)
- [Evaluation](#evaluation)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Sentiment analysis is a natural language processing (NLP) task used to determine the sentiment or emotion expressed in a piece of text. In this project, we use the IMDB dataset to build models that classify movie reviews as positive or negative. We implement three different models:
- A simple Recurrent Neural Network (RNN)
- A Long Short-Term Memory (LSTM) network
- A Transformer model

## Dataset
We use the IMDB movie review dataset, which consists of 50,000 reviews:
- 25,000 reviews for training
- 25,000 reviews for testing

Each review is labeled as either positive or negative. The dataset is balanced, with an equal number of positive and negative samples.

## Model Architectures
1. **RNN Model**: A basic recurrent neural network that learns from sequential text data.
2. **LSTM Model**: An improved version of the RNN that addresses the vanishing gradient problem and captures long-term dependencies.
3. **Transformer Model**: A modern architecture that uses self-attention mechanisms for efficient learning from text sequences.

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis
   cd sentiment-analysis
