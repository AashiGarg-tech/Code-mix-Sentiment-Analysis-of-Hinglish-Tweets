# Code-Mixed Hinglish Sentiment Analysis using Multilingual BERT

## Overview
This project uses Multilingual BERT (mBERT) to classify code-mixed Hinglish tweets into Positive, Neutral, and Negative sentiment categories. The model addresses challenges such as mixed Hindi-English text, informal spellings, abbreviations, and emojis commonly found on social media platforms.

## Features
- Multi-class sentiment classification
- Hinglish text preprocessing and normalization
- Emoji-aware sentiment handling
- Fine-tuning of pretrained Multilingual BERT
- Classification of Positive, Neutral, and Negative sentiments

## Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- Multilingual BERT (mBERT)
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Google Colab

## Dataset
Combined Hinglish Sentiment Datasets

- Total Tweets after Deduplication: 29,098
- Final Preprocessed Tweets: 28,841
- Positive Tweets: 9,500
- Neutral Tweets: 10,764
- Negative Tweets: 8,577

## Model Architecture
- Hinglish Text Preprocessing Pipeline
- BERT Tokenizer
- Multilingual BERT (bert-base-multilingual-cased)
- Sequence Classification Head
- Softmax Output Layer (3 Classes)

## Results
- Test Accuracy: 74.93%
- Macro F1 Score: 75.29%
- Validation Accuracy: 73.43%
- Validation Macro F1 Score: 73.74%

## Sample Prediction
The trained model can analyze code-mixed Hinglish tweets and predict sentiment as Positive, Neutral, or Negative with confidence scores.

## Future Improvements
- Larger code-mixed datasets
- Support for additional Indian languages
- Advanced transformer architectures
- Real-time sentiment monitoring dashboard
- Explainable AI for sentiment interpretation
