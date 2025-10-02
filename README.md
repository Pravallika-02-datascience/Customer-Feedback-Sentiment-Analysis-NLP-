# Customer-Feedback-Sentiment-Analysis-NLP
# Sentiment Analysis — Project

**Author:** Addagalla Pravallika  
**Project type:** NLP / Supervised Learning — Sentiment Classification from Product Reviews  
**Language:** Python

## Project Overview

This repository contains a sentiment analysis project that preprocesses textual data, extracts features (TF-IDF / embeddings), trains classification models (e.g., Logistic Regression, Random Forest), and evaluates model performance with accuracy and cross-validation. The original notebook (`Sentiment_Analysis.ipynb`) was converted into a clean, single-file script for clarity and reproducibility.

## What I delivered

- `Sentiment_Analysis.ipynb` — original exploratory notebook (kept in the repo).
- `Sentiment_Analysis final.py` — cleaned, consolidated Python script suitable for GitHub and reuse.
- `requirements.txt` — list of Python packages required to run the project.

## Installation

```bash
# create a venv (recommended)
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate       # Windows

# install dependencies
pip install -r requirements.txt
```

## Usage

1. Place your dataset file (e.g. `reviews.csv`) in the repository root or update the path inside the script/notebook.
2. Open and run the notebook for exploratory visuals, or run the cleaned script:

```bash
python Sentiment_Analysis_clean.py
```

3. Inspect model results, confusion matrices, and saved artifacts (if any).

## Notebook → Script notes

- The code in `Sentiment_Analysis_clean.py` is a direct, cleaned extraction from `Sentiment_Analysis.ipynb`. Magic commands, shell calls, and interactive-only lines were removed for portability.
- Before running the script, verify dataset paths and any API keys or file paths referenced.

## Results & Insights

- The notebook contains the EDA and model evaluation results. Key model(s) and metrics (e.g. accuracy, cross-validation score) are available in the notebook outputs.
- Typical pipeline: text cleaning → tokenization → TF-IDF → model training (Logistic Regression often performs well for baseline) → evaluation.

Streamlit file link : https://sentimentanalysis-app-ctenkjk48urxzuudzft2pk.streamlit.app/


## Contact

Addagalla Pravallika — `a.pravallika86@gmail.com` 

---
