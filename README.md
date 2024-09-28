# Hybrid Retrieval-Augmented Generation (RAG) System

## Project Overview
This repository contains an implementation of a **Retrieval-Augmented Generation (RAG)** system that combines both sparse and dense retrieval techniques to enhance information retrieval from documents. The system is designed to effectively process PDF documents, extract relevant information, and provide contextually appropriate responses to user queries.

## Contents
- **Notebooks**: Jupyter notebooks containing code for embedding comparison, chunking experiments, and PDF loading.
- **PDF Document**: The source document used for testing the retrieval system.
- **README.md**: This file.

## Key Features
- **Hybrid Retrieval**: Combines sparse retrieval (using BM25) and dense retrieval (using OpenAI embeddings).
- **Chunking Strategies**: Experiments with paragraph-based, recursive, and semantic chunking methods to determine their impact on retrieval quality.
- **PDF Loaders**: Utilizes multiple loaders (PyPDFLoader, PDFPlumberLoader, PyMuPDFLoader) to extract text from PDF documents.

## Getting Started
### Prerequisites
To run the code in this repository, ensure you have the following installed:
- Python 3.x
- Required Python packages (see installation instructions below)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
