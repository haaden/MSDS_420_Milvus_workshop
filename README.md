# Milvus Workshop: Semantic Search

This repository contains two Google Colab notebooks for learning **Milvus**, an open-source vector database. These workshops demonstrate how to build semantic search engines using real-world datasets.

## 📂 Notebooks

### 1. [Epstein Case Files Search](./milvus_workshop_epstein_case_files.ipynb)
* **Focus:** Document retrieval from investigative legal files.
* **Key Tech:** Cosine similarity and metadata "Hydration" to retrieve specific file excerpts.

### 2. [IMDB Sentiment Search](./milvus_workshop_imdb_reviews.ipynb)
* **Focus:** Filtered semantic search on movie reviews.
* **Key Tech:** Combining vector similarity with metadata filters (e.g., searching specifically for "Positive" reviews).

---

## 🛠️ Core Concepts Covered
* **Vector Storage:** Storing text and ratings alongside vector embeddings.
* **Output Fields:** Using `output_fields` to return original data instead of just IDs.
* **Efficiency:** Best practices for handling large metadata by linking to external storage.

## 📋 Requirements
* **Environment:** Google Colab (T4 GPU recommended).

## 🚀 Getting Started
1. Open a notebook in [Google Colab](https://colab.research.google.com/).
2. Set runtime to **T4 GPU**.
3. Run cells to install dependencies and execute the search workflows.
