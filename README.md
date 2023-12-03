# Simple-Search-Engine
 The Simple Search Engine project is a lightweight yet powerful tool designed to provide efficient text search capabilities. this project allows users to search through a corpus of documents and obtain relevant result.
The Vector Space Model (VSM) is a crucial concept in Natural Language Processing (NLP) used to represent text data numerically in a high-dimensional space. This project implements a search engine using the VSM approach, allowing users to retrieve relevant information from a given corpus.

## Description

This search engine project involves several key steps:

### Step 0: Importing Corpus

The initial step involves reading text corpora from the local machine. The Python script utilizes the NLTK library for further processing.

### Step 1: Preprocessing & Tokenizing

Text preprocessing is carried out to eliminate unnecessary tokens and simplify calculations. The NLTK library is employed for tasks such as tokenization, lemmatization, and stop-word removal.

### Step 2: Creating our Dataset

The preprocessed data is organized into a CSV file, creating a structured dataset for subsequent analysis.

### Step 3: Creating our Matrix

A term-document matrix is generated from the dataset, representing the frequency of terms in each document.

### Step 5: Calculating Cosine Similarity

Cosine similarity is computed to measure the similarity between the input query and the documents in the corpus. The results are ranked based on similarity.

## How to Use

1. Clone the repository to your local machine.
2. Install the necessary dependencies (NLTK, pandas).
3. Run the Python script to build the search engine.

## Dependencies

- NLTK
- Pandas

## Author

[Kiarash Rahmani]

## License

This project is licensed under the [MIT License](LICENSE).

