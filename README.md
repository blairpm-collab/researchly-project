# Researchly: AI Research Paper Analytics

## Project Overview
This repository fulfills the SAnalytics "Researchly" requirements for data science research analytics. It includes natural language processing (NLP), machine learning classification, topic analysis, and web deployment using Python.

## Project Structure

### 1. Datasets
- `research_abstracts.json`: Contains the JSON data for research abstracts used in Q1 and Q2.
- `research_corpus.zip`: Contains the PDF research articles used for topic mining in Q3 and Q4.

### 2. Notebooks (Q1 - Q4)
- **Q1 & Q2 (Classification):** 
  - Preprocessing and text denoising.
  - Baseline model (Multinomial Naive Bayes).
  - Four advanced models (Logistic Regression, SVM, Random Forest, MLP).
  - Hyperparameter tuning using RandomizedSearchCV.
- **Q3 (Topic Analysis):**
  - Extracted and processed the PDF research corpus.
  - Summarization using TF-IDF sentence scoring (Extractive) for Article 1.
  - Aggregate summarization using NMF Topic Modeling and Word Clouds.
- **Q4 (LDA Modelling):**
  - Latent Dirichlet Allocation (LDA) for extracting top topics.
  - Interactive intertopic distance map generated using `pyLDAvis`.

### 3. Deployment (Q1 & Q2)
The `deployment` folder contains the working Streamlit web interface to test the best-performing classifier model.
- See `deployment/README.md` for instructions on how to launch the app locally.
