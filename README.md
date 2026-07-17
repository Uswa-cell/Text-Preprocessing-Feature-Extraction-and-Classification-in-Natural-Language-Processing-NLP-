# Text Preprocessing & Feature Extraction Pipeline (NLP)

A hands-on implementation of core NLP preprocessing techniques — from raw text to numerical feature representations — using Python.

## Overview
This project demonstrates the complete text preprocessing pipeline that underlies most NLP systems:

Raw Text → Tokenization → Normalization → Feature Extraction

## Pipeline Steps
1. **Tokenization** — splitting text into individual words
2. **Case normalization** — converting to lowercase for consistency
3. **Number removal** — cleaning non-alphabetic noise
4. **Lemmatization** — reducing words to their dictionary base form (e.g., "learning" → "learn")
5. **Stemming** — reducing words to their root form (e.g., "coding" → "code")
6. **Count Vectorization** — converting text into word-frequency vectors
7. **TF-IDF** — weighting words by importance across the text, not just raw frequency

## Example Output
Word frequency analysis, lemmatized/stemmed tokens, and TF-IDF feature vectors are generated and printed at each pipeline stage, showing how raw text is progressively transformed into a machine-readable numerical format.

## Tech Stack
Python · NLTK · Scikit-learn · Pandas · NumPy

## Note
This project focuses on the preprocessing and feature-engineering pipeline itself rather than end-to-end classification accuracy — it's a foundational demonstration of the steps every text classification system depends on.

## Author
Uswa Aslam
