# 🧠 Word Embedding using Word2Vec

This project demonstrates how to train and visualize **Word2Vec** word embeddings using a custom corpus. Word embeddings are a fundamental technique in Natural Language Processing (NLP) for representing words in dense vector space based on their context and semantic meaning.

## 📘 Project Overview

Word2Vec is a popular algorithm developed by Google that converts words into high-dimensional vectors. Words that appear in similar contexts have similar vector representations. This notebook implements the Word2Vec model using the `gensim` library and includes the following components:

- Text preprocessing and tokenization
- Training Word2Vec on a sample corpus
- Exploring word similarities and analogies
- Visualizing embeddings using dimensionality reduction (e.g., PCA or t-SNE)


## 🔧 Technologies Used

- **Python 3**
- **Gensim** – for Word2Vec implementation
- **NLTK** – for text preprocessing 
- **Scikit-learn / Matplotlib / Seaborn** – for visualization
- **Pandas / NumPy** – for data handling

## 🔍 Features

- Build Word2Vec models using Skip-gram or CBOW
- Query similar words: e.g., model.wv.most_similar('king')
- Explore analogies: e.g., king - man + woman ≈ queen
- Visualize embeddings in 2D using PCA/t-SNE

## 📈 Example Output

```pgsql
Most similar to 'king': [('queen', 0.89), ('monarch', 0.82), ('prince', 0.78)]
Analogy: king - man + woman ≈ queen
```

## 📚 Future Enhancements
- Train on larger or domain-specific corpora
- Compare performance with FastText or GloVe
- Save and load trained models for reuse
