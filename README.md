# Language Generation Models: Transformer and Bi-LSTM Architectures

## Overview
Language generation models have become a cornerstone of Natural Language Processing (NLP), enabling machines to produce human-like text based on given inputs. This project focuses on developing and training two distinct architectures for language generation:
- A custom **Transformer-based model**.
- A **Recurrent Neural Network (RNN)** model using a bidirectional Long Short-Term Memory (Bi-LSTM) network.

Both architectures were designed and evaluated to explore their unique strengths in handling the complexities of language modeling.

---

## Objectives
- **Build and train** two language generation models (Transformer and Bi-LSTM) for text generation.
- Leverage domain-specific data curated from government and education-related websites.
- Incorporate **custom embeddings** and **pre-trained embeddings (GloVe-200)** to enhance model performance.
- Evaluate models using standard metrics like **accuracy** and **BLEU scores**.

---

## Dataset
The dataset was curated by **web scraping** from:
1. **Higher Education Commission (HEC)** website.
2. **Government of Pakistan** website.

### Dataset Details:
- The scraped data was merged into a **CSV file**.
- It provides a **rich, domain-specific corpus** tailored for generating relevant and meaningful text in the context of education and governance.

---

## Methodology
1. **Data Preparation**:
   - Scraped and preprocessed textual data from the HEC and Government of Pakistan websites.
   - Tokenized and cleaned the text for uniformity and to remove noise.
   - Created embeddings:
     - **Custom embeddings** based on the curated dataset.
     - **Pre-trained embeddings (GloVe-200)** to leverage semantic and syntactic knowledge.

2. **Model Architectures**:
   - **Transformer-based Model**:
     - Utilized attention mechanisms to capture long-range dependencies in text.
     - Excelled at generating coherent and contextually relevant sentences.
   - **Bi-LSTM Model**:
     - Leveraged sequential processing to learn contextual information from both past and future states.
     - Provided robust results for tasks requiring fine-grained contextual understanding.

3. **Training**:
   - Both models were trained on the curated dataset.
   - Implemented supervised learning with the objective to predict the next **n words** based on user input.

4. **Evaluation**:
   - Used **accuracy** and **BLEU scores** to assess the syntactic correctness and semantic relevance of the generated text.

---

## Features
- **Custom Data Integration**: Combined HEC and Government of Pakistan datasets to create a unique, domain-specific corpus.
- **Dual Embedding Strategy**:
  - Custom embeddings for domain relevance.
  - Pre-trained GloVe-200 embeddings for robust word representation.
- **Transformer Model**: Captures long-range dependencies effectively.
- **Bi-LSTM Model**: Leverages sequential processing for contextual understanding.
- **Text Generation**: Allows users to specify **n words** for prediction and generates coherent text accordingly.

---

## Results
- **Transformer Model**:
  - Excelled at capturing long-range dependencies and generated fluent text.
  - Achieved higher BLEU scores for contextually complex tasks.
- **Bi-LSTM Model**:
  - Performed well in tasks requiring short-range context understanding.
  - Complemented the Transformer in simpler text generation scenarios.

---
