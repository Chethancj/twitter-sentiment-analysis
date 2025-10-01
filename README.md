
---

# 3️⃣ Twitter Sentiment Analysis



## Overview
NLP project to classify tweets as Positive, Negative, or Emotion-based.  
It combines **traditional ML, deep learning, and visual storytelling**.

## Dataset
- Custom dataset (CSV) with columns:  
  - `text` → Tweet text  
  - `label` → Sentiment (0/1 or multi-class)  

## Workflow
1. Data Cleaning (remove URLs, mentions, punctuation)  
2. Feature Extraction  
   - TF-IDF vectorisation  
3. Model Training  
   - Logistic Regression (baseline)  
   - LSTM with Keras  
4. Evaluation  
   - Accuracy, Precision, Recall, F1  
5. Visualisation (NEW)  
   - Word Clouds for Positive vs Negative tweets  
6. Emotion Classification (NEW)  
   - Expanded to Joy, Anger, Sadness, Surprise  

## Results
- Logistic Regression F1: **~0.75**  
- LSTM Accuracy: **~82%**  
- Word clouds highlight dominant themes in sentiment  

## Usage
```bash
pip install -r requirements.txt
python sentiment_train.py
