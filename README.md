# NLP N-gram Movie Review Classifier

This repository contains the code for my NLP assignment, where I built N-gram models from scratch and used them to classify movie reviews. The project includes the implementation of unigram, bigram, and trigram models for word prediction and Bayesian classification of movie reviews.

## Project Overview

### 1. **Text Prediction using N-gram Models**
   - **Objective**: To predict the next word in a sequence using unigram, bigram, and trigram models.
   - **Models Implemented**:
     - **Unigram Model**: Predicts the most frequent word in the corpus.
     - **Bigram Model**: Predicts the next word based on the previous word.
     - **Trigram Model**: Predicts the next word based on the previous two words.
   - **Prediction Function**: A function that predicts the next word based on the preceding words without using off-the-shelf libraries.

### 2. **Movie Review Classification**
   - **Objective**: To label movie reviews using Bayesian classification based on the N-gram models built from the corpus.
   - **Approach**:
     - Build unigram, bigram, and trigram models from the movie review dataset.
     - Use the Bayesian classification function to suggest labels for movie reviews.
     - Evaluate the classification performance using standard metrics such as accuracy, precision, and recall.

## Features

- Build N-gram models (Unigram, Bigram, Trigram) from a text corpus.
- Predict the next word in a sequence using these models.
- Classify movie reviews based on the generated language models.
- Evaluate the classification using standard metrics.

## Installation

To run this project, you'll need:

- Python 3.x
- Jupyter Notebook


