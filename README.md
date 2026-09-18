# Hybrid RAG – Retrieval-Augmented Generation

## Project Overview

This project implements a **Hybrid Retrieval-Augmented Generation (RAG)** system that combines **Keyword Retrieval** and **Semantic Retrieval** to find relevant documents and generate accurate, context-aware answers.

## Workflow

```text
User Query
    ↓
Keyword Retrieval + Semantic Retrieval
    ↓
Hybrid Scoring
    ↓
Relevant Documents
    ↓
Context
    ↓
Generation
    ↓
Answer
```

## Hybrid Score

```text
Hybrid Score = α × Keyword Score + (1 − α) × Semantic Score

For α = 0.5:

Hybrid Score = 0.5 × Keyword Score + 0.5 × Semantic Score
```

## Evaluation

**Precision:**

```text
Precision = Relevant Retrieved Documents / Total Retrieved Documents
```

**Recall:**

```text
Recall = Relevant Retrieved Documents / Total Relevant Documents
```

## Technologies Used

* Python
* NLP
* Semantic Search
* Text Embeddings
* Generative AI
* RAG

## Objective

To improve document retrieval by combining **keyword matching and semantic similarity**, and use the retrieved information to generate relevant answers.

## Author

**Gundlakunta Madhuri Reddy**
**B.Tech – Data Science**
