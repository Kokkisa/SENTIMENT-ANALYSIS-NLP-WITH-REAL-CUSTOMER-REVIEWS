# SENTIMENT-ANALYSIS-NLP-WITH-REAL-CUSTOMER-REVIEWS[README_project6.md](https://github.com/user-attachments/files/25735071/README_project6.md)
# 📝 Sentiment Analysis — NLP with Customer Reviews

## Overview
Natural Language Processing project analyzing customer review sentiment using three approaches: rule-based (TextBlob, VADER) and machine learning (Logistic Regression + TF-IDF). Demonstrates text preprocessing, feature extraction, and sentiment classification on unstructured text data.

**Built by:** Nithin Kumar Kokkisa — Senior Demand Planner with 12+ years in manufacturing operations & supply chain analytics.

---

## Business Problem
Companies receive thousands of customer reviews but can't manually read them all. This project automates sentiment detection to identify unhappy customers, track product satisfaction trends, and extract key themes from review text.

## Approach

### Text Preprocessing Pipeline
- Lowercase conversion, punctuation removal, number removal
- Tokenization (splitting text into words)
- Stopword removal (removing filler words: the, is, and, etc.)

### Three Sentiment Analysis Methods
1. **TextBlob** — Dictionary-based polarity scoring (-1 to +1)
2. **VADER** — Social media/review-tuned sentiment (handles negation, intensity, caps)
3. **ML Classification** — Logistic Regression trained on TF-IDF features

### Feature Engineering
- **Bag of Words** (CountVectorizer) — word count matrix
- **TF-IDF** (Term Frequency-Inverse Document Frequency) — weighted word importance
- **N-grams** — bigrams capture phrases like "highly recommend" and "waste money"

## Key Results

| Method | Accuracy |
|--------|----------|
| TextBlob | TBD |
| VADER | TBD |
| ML (LogReg + TF-IDF) | TBD |

## Visualizations

| Chart | Insight |
|-------|---------|
| Word Clouds | Most frequent words overall and by sentiment |
| Sentiment Distributions | VADER vs TextBlob score separation |
| Confusion Matrix | ML classification performance |
| Important Words | Top predictive words per sentiment class |
| Bigram Analysis | Most common 2-word phrases by sentiment |
| Method Comparison | Accuracy comparison across all three approaches |

## NLP Concepts Demonstrated
- Text preprocessing and cleaning pipeline
- Tokenization and stopword removal
- Bag of Words vs TF-IDF feature extraction
- Rule-based vs ML-based sentiment analysis
- N-gram analysis (bigrams, trigrams)
- Model evaluation with classification report

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **TextBlob** — Rule-based sentiment
- **VADER** — Social media sentiment analysis
- **scikit-learn** — TF-IDF, Logistic Regression, metrics
- **WordCloud** — Text visualization

---

## About
Part of a **30-project data analytics portfolio**. See [GitHub profile](https://github.com/Kokkisa) for the full portfolio.

**Previous Projects:**
- [Project 1 — Demand Forecasting with Prophet](https://github.com/Kokkisa/demand-forecasting-prophet)
- [Project 2 — ARIMA vs Prophet vs ETS](https://github.com/Kokkisa/forecasting-model-comparison)
- [Project 3 — Customer Churn Prediction with SHAP](https://github.com/Kokkisa/customer-churn-prediction)
- [Project 4 — SQL Business Analytics](https://github.com/Kokkisa/sql-business-analytics)
- [Project 5 — Interactive Sales Dashboard](https://github.com/Kokkisa/sales-analytics-dashboard)
