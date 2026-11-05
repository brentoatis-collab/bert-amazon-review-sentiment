> **Applied AI portfolio project by Brent Oatis, MBA**
> Turning unstructured customer feedback into measurable decision signals with BERT.

# BERT Sentiment Classification – Amazon Polarity

## Overview
This project builds and optimizes a BERT-based sentiment classification model using the Amazon Polarity dataset. The model classifies customer reviews as positive or negative and evaluates performance using precision, recall, F1-score, and accuracy.

## Dataset
- Amazon Polarity (Hugging Face)
- 500 training samples
- 200 testing samples

## Models Implemented

### Base Model
- BERT + Dropout + Linear layer
- 3 epochs
- Batch size: 16

### Optimized Model (V2)
- BERT + Dropout + Dense + ReLU + Dense
- 5 epochs
- Batch size: 32

## Results

### Base Model
- Accuracy: 0.835
- Precision: 0.952
- Recall: 0.734
- F1 Score: 0.829

### Optimized Model
- Accuracy: 0.870
- Precision: 0.895
- Recall: 0.862
- F1 Score: 0.878

## Key Insights
- Deeper classification head improved model balance
- Increased recall significantly
- Higher F1 score indicates better generalization

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn

## Files
- Week4_BERT_Sentiment.ipynb
- base_model_results.csv
- v2_model_results.csv
