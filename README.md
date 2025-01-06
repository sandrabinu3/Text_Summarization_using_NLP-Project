# Traditional Vs Transformer Models in NLP: A Comparative Study on Text Summarization
This repository contains the code and resources for the project "Traditional Vs Transformer Models in NLP: A Comparative Study on Text Summarization". The study explores the performance of traditional extractive summarization models (TextRank and Word2Vec) compared to the transformer-based T5 model, utilizing the CNN/Daily Mail dataset.

## Overview
The goal of this project is to implement and compare different text summarization techniques, focusing on the trade-offs between computational efficiency and summarization quality.

### **Dataset:**

**CNN/Daily Mail Dataset** – A large-scale dataset containing news articles and highlights used for training and evaluating summarization models.

**Core Libraries:**
* transformers (for transformer models like BERT and T5)
* torch (for deep learning model implementations)
* sklearn (for traditional NLP methods and metrics)
* pandas (for dataset handling and manipulation)
* nltk (for text preprocessing and tokenization)

## Methodology
### Data Preprocessing
* Text Cleaning: Removing unnecessary punctuation, special characters, and formatting.
* Tokenization: Splitting the text into words or subwords for model processing.
### Models' Implemetation
1. TextRank with TF-IDF 

2. Word2Vec with Sentence Scoring

3. T5-Small (Transformer)

### Evaluation Metrics
* **ROUGE Score**: Measures the quality of the summaries.
* **Inference Time** : For calculating computational efficiency

## Results
Transformer based model(T5) outperformed traditional models(TextRank and Word2Vec) in generating insightful summaries even though traditional models were better in terms of computational efficiency.
