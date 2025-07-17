# MATLAB-Project
# 📚 Information Retrieval System

This repository contains the implementation and evaluation of an Information Retrieval (IR) system developed using the **Cranfield Collection** as part of **CE205: Databases and Information Retrieval** at the University of Essex.

## 🔍 Assignment Objective

To design and evaluate an IR system that retrieves and ranks documents based on their similarity to a user query using two core models:
- Bag-of-Words (BoW)
- TF-IDF (Term Frequency-Inverse Document Frequency)

## 🧩 Tasks Overview

### ✅ Task A – Bag-of-Words Model [20%]
- Preprocessed 1400 documents from the Cranfield Collection
- Cleaned text by converting to lowercase, removing stop words, punctuation, and applying stemming
- Created a BoW representation using MATLAB/Python
- Visualized top frequent terms using word cloud

### ✅ Task B – Document Ranking using BoW [25%]
- Selected 5 queries from Appendix A
- Preprocessed and encoded queries into BoW vectors
- Computed cosine similarity between each query and document
- Ranked and displayed top 20 relevant documents per query

### ✅ Task C – Document Ranking using TF-IDF [25%]
- Computed TF-IDF weights for the BoW matrix
- Encoded the same 5 queries into TF-IDF vectors
- Computed cosine similarity and ranked documents
- Compared results to BoW-based retrieval

### ✅ Task D – Evaluation of IR System [30%]
- Used `Query-Doc.xlsx` relevance file to compute:
  - Precision@10, Recall@10
  - Precision@20, Recall@20
- Compared BoW vs TF-IDF performance

## 📄 Report

The full report, including code snippets, screenshots, and analysis, is available in this repository:

👉 [2316794_CE205_Assignment2.pdf](./2316794_CE205_Assignment2.pdf)

## ⚙️ Tools Used

- MATLAB R2023a (Text Analytics Toolbox) or Python (optional)
- Cosine Similarity
- Preprocessing (lowercase, stop words removal, stemming)
- Word Clouds for visualization
- Excel for relevance mapping (`Query-Doc.xlsx`)

## 📌 Notes

- All processing was automated (no manual document ranking)
- Assignment submitted to FASER as per university guidelines
- All code was written individually as per plagiarism policy

## ✍️ Author

**Sneha Tandon**  
University of Essex  
Registration No: 2316794  
Module: CE205 – Databases and Information Retrieval  

---

> This project was completed as part of coursework. For educational and demonstration purposes only.
