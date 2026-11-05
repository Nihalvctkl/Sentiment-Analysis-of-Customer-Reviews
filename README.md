# Comparative Analysis of Machine Learning and Deep Learning Approaches for Sentiment Analysis of Customer Reviews

## 📌 Project Overview

This project focuses on analyzing customer reviews and classifying them into three sentiment categories: **Positive, Negative, and Neutral**.

It explores and compares different deep learning architectures and feature extraction techniques to understand their effectiveness in sentiment classification. The project also investigates the impact of model architecture and TF-IDF feature representation through an ablation study.

## 🎯 Objectives

- Perform sentiment analysis on customer reviews.
- Classify reviews into Positive, Negative, and Neutral categories.
- Implement and evaluate different neural network architectures.
- Explore TF-IDF unigram and bigram feature extraction.
- Conduct an ablation study to analyze the contribution of different neural network layers.
- Compare model performance using evaluation metrics.

## 📂 Dataset

**Dataset:** Customer Review Sentiment Dataset (CRSD)

**Source:** [Hugging Face – CRSD](https://huggingface.co/datasets/InfinitodeLTD/CRSD)

The dataset contains customer reviews with three sentiment labels:

- Positive
- Negative
- Neutral

## 🧠 Models and Approaches

The project contains four notebooks:

### 1. LSTM-Based Sentiment Analysis
- Long Short-Term Memory (LSTM)
- Embedding layer
- Three-class sentiment classification

### 2. RNN-Based Sentiment Analysis
- Simple Recurrent Neural Network (RNN)
- Embedding layer
- Three-class sentiment classification

### 3. TF-IDF-Based FNN with Ablation Study
- TF-IDF feature extraction
- Feedforward Neural Network (FNN)
- Ablation study to evaluate the contribution of individual network layers and dropout.

### 4. TF-IDF Unigram-Bigram-Based FNN
- TF-IDF feature extraction
- Unigram and bigram features
- Feedforward Neural Network
- Early stopping comparison

## ⚙️ Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Natural Language Processing (NLP)

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🚀 Execution

1. Open Google Colab.
2. Upload the required dataset.
3. Open the respective notebook.
4. Install the required dependencies if necessary.
5. Execute the code cells sequentially.
6. Observe the training results and evaluation metrics.

## 📁 Repository Contents

The repository contains four sentiment analysis notebooks and their corresponding PDF versions for easy viewing and reference.

## 🎓 Project Information

**Project Title:** Comparative Analysis of Machine Learning and Deep Learning Approaches for Sentiment Analysis of Customer Reviews

**Domain:** Artificial Intelligence, Machine Learning, Deep Learning and Natural Language Processing (NLP)

---

*This project is developed for academic and research purposes to study and compare different approaches to customer review sentiment analysis.*
