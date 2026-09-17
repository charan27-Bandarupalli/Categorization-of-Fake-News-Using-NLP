# Categorization-of-Fake-News-Using-NLP
NLP-based Fake News Classification Case Study — Explores fake and factual news using Natural Language Processing techniques, including POS tagging, named entity extraction, text preprocessing, sentiment analysis, and topic analysis to identify patterns in news content.

This project uses **Natural Language Processing (NLP)** techniques to analyze and classify news articles as **Fake News** or **Factual News**.

##  Project Overview

The project explores different NLP techniques to understand patterns in news articles and classify them into fake or factual categories.

## What This Project Covers

- Data exploration and visualization
- Part-of-Speech (POS) tagging
- Named Entity Recognition (NER)
- Text preprocessing
- Sentiment analysis
- Topic modeling using LDA
- TF-IDF and LSA
- Text vectorization using CountVectorizer
- Fake vs. factual news classification
- Model evaluation

## Machine Learning Models

The project uses:

- Logistic Regression
- SGD Classifier

### Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 90.00% |
| SGD Classifier | 88.33% |

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- spaCy
- Gensim
- Scikit-learn

##  Dataset

The dataset contains **198 news articles**:

- 98 Fake News articles
- 100 Factual News articles

The main columns are:

- `title`
- `text`
- `date`
- `fake_or_factual`

## How to Run

Clone the repository:

```bash
git clone https://github.com/charan27-Bandarupalli/Categorization-of-Fake-News-Using-NLP.git
