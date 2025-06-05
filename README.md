# Fake News Detection System

A machine learning system that leverages advanced NLP techniques and CatBoost to accurately classify news articles as real or fake.

## Features

- Advanced text preprocessing and cleaning
- Sentiment analysis using TextBlob
- Lexical diversity and readability metrics
- Sentence embeddings using SentenceTransformer
- Dimensionality reduction with PCA
- CatBoost classifier for robust classification
- Comprehensive feature engineering
- High-accuracy predictions

## How It Works

### 1. Text Preprocessing
- URL removal
- HTML tag cleaning
- Accented character normalization
- Special character removal
- Contraction expansion
- Sentiment analysis (polarity and subjectivity)

### 2. Feature Engineering
- Word count and character count
- Reading time estimation
- Readability scores (Linsear Write)
- Lexical diversity calculation
- Words per sentence
- Sentiment metrics

### 3. Text Encoding
- SentenceTransformer for generating embeddings
- PCA for dimensionality reduction
- Feature concatenation

### 4. Model Training
- CatBoost classifier
- LogLoss optimization
- 900 iterations
- Learning rate: 0.002
- 80-20 train-validation split

### 5. Prediction Pipeline
- Test data preprocessing
- Feature generation
- Model inference
- CSV submission generation

## Model Performance

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- LogLoss

## Technical Details

### Key Components

1. **Text Processing**
   - Custom cleaning pipeline
   - Sentiment analysis
   - Readability metrics
   - Lexical diversity calculation

2. **Feature Engineering**
   - Statistical metrics
   - Linguistic features
   - Sentiment scores
   - Embedding generation

3. **Model Architecture**
   - CatBoost classifier
   - PCA dimensionality reduction
   - SentenceTransformer embeddings

4. **Evaluation System**
   - Multiple metric tracking
   - Cross-validation
   - Performance visualization
