# Sentiment Analysis on Audio Data using Support Vector Machines (SVM)

## 1. Introduction

Sentiment analysis, also known as opinion mining, is a growing field within natural language processing that aims to understand subjective information in textual and audio data. This study focuses on sentiment analysis applied to audio data, exploring emotional expression in spoken language.

### 1.1 Background

Emotions conveyed through speech offer valuable insights into individuals' sentiments, attitudes, and opinions. Analyzing these emotions in audio data presents unique challenges compared to text-based sentiment analysis.

### 1.2 Problem Statement

This study addresses the complexity of interpreting emotions from speech signals and aims to develop robust models for accurately classifying emotional states in audio data.

### 1.3 Objectives

The primary objectives of this research are:
- Implement sentiment analysis on audio data from datasets such as Ravdess, Crema, and TESS.
- Extract relevant features, such as Mel-Frequency Cepstral Coefficients (MFCCs), from audio signals.
- Use Support Vector Machines (SVM) for emotion classification.
- Evaluate and compare the performance of the model before and after optimization through feature scaling and hyperparameter tuning.

## 2. Materials and Methods

### 2.1 Data Collection

Audio data was sourced from Ravdess, Crema, and TESS datasets, providing a diverse collection of emotional expressions in speech.

### 2.2 Data Processing

Steps involved in processing audio datasets included data augmentation techniques to enhance the model's robustness and diversity.

#### 2.2.1. Ravdess Dataset Processing

- Access audio files and extract relevant information.
- Map emotion labels based on predefined dictionaries.
- Consolidate processed information into a Pandas DataFrame.

#### 2.2.2. Crema Dataset Processing

- Access audio files and extract relevant information from filenames.
- Map emotion labels using predefined dictionaries.
- Determine gender information based on a list of female IDs.
- Consolidate processed information into a Pandas DataFrame.

#### 2.2.3. TESS Dataset Processing

- Access audio files and extract relevant information.
- Map emotion labels based on predefined dictionaries.
- Consolidate processed information into a Pandas DataFrame.

## 3. Results and Discussions

### 3.1 Overview

The initial SVM model without modification yielded a classification report and confusion matrix.

### 3.2 Improved Model

Enhancements including feature scaling and hyperparameter tuning significantly improved the model's performance. The refined SVM model demonstrated enhanced precision, recall, and overall accuracy.

### 3.3 Interpretation and Discussion

Feature scaling and hyperparameter tuning played a crucial role in improving the model's accuracy and generalization. The upgraded model signifies a significant advancement in sentiment analysis for audio data.

## 4. Conclusions

The study's findings contribute to the field of sentiment analysis, particularly in accurately classifying emotions in audio data. The refined SVM model, equipped with feature scaling and optimized hyperparameters, stands as a robust tool for this task.

