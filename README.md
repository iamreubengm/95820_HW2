# 95820_HW2

# RAG System: From Naive to Production Patterns

A comprehensive implementation of Retrieval-Augmented Generation (RAG) systems for question-answering on the RAG Mini Wikipedia dataset, demonstrating progression from naive baselines to production-ready enhancements. Created for the seecond assignment in 95820: Applications of NL(X) and LLM

## Overview

This project implements and evaluates multiple RAG architectures, comparing embedding dimensions, retrieval strategies, and prompting techniques. The system achieves a **124% F1 score improvement** over no-retrieval baselines and provides insights into optimal production configurations.

## Key Features

- **Multiple Embedding Dimensions**: Comparison of 384d (all-MiniLM-L6-v2) vs 768d (all-mpnet-base-v2) embeddings
- **Retrieval Strategies**: Top-1, Top-3, and Top-5 context retrieval evaluation
- **Prompting Techniques**: Persona and Chain-of-Thought prompting
- **Enhanced RAG**: Confidence-based adaptive context selection and context window optimization
- **Comprehensive Evaluation**: Traditional metrics (EM, F1) and RAGAs metrics (faithfulness, answer relevancy, context precision/recall)

## Installation (If running locally)
```bash
pip install -r requirements.txt
```

## Usage
### Running on Google Colab

- Upload the notebook to Google Colab
- Enable GPU runtime (Runtime → Change runtime type → GPU → T4)
- Run all cells sequentially

The notebook includes:
- Exploratory Data Analysis (EDA) on the dataset
- Naive RAG implementation with multiple configurations
- Enhanced RAG with adaptive strategies
- Comprehensive evaluation using traditional and RAGAs metrics


