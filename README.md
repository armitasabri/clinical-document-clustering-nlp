# Clinical Document Clustering with NLP and Machine Learning

## Overview
This project explores unsupervised clustering of clinical case reports using natural language processing and machine learning techniques. The goal is to group similar clinical documents into meaningful topics based on textual content.

The workflow includes text preprocessing, feature engineering, topic modeling, clustering, and visualization. The project also compares classical sparse text representations with distributed embeddings.

## Main Contributions
- Preprocessed clinical text using tokenization, lemmatization, stopword removal, and domain-specific cleaning
- Built document representations using TF-IDF and augmented term frequency
- Applied Non-negative Matrix Factorization (NMF) for topic extraction
- Used Word2Vec embeddings for alternative semantic representation
- Clustered documents and visualized cluster structure using PCA
- Reflected on methodological similarities and differences with a published clinical document clustering paper

## Methods
### Text Preprocessing
- Removed punctuation and stopwords
- Filtered domain-specific non-informative terms
- Preserved informative nouns and adjectives
- Applied tokenization and lemmatization

### Feature Engineering
- TF-IDF document-term matrix
- Augmented term frequency
- Word2Vec embeddings

### Modeling and Analysis
- NMF for interpretable topic modeling
- K-Means for clustering
- PCA for 2D visualization
- Topic-word inspection for qualitative evaluation

## Repository Structure
```text
.
├── notebooks/
│   ├── PA-Clustering_words.ipynb
│   ├── my_word_clustering.ipynb
│   └── word_embedding.ipynb
├── docs/
│   └── paper_analysis.txt
├── README.md
├── requirements.txt
└── .gitignore

## Tools and Libraries

- Python
- pandas
- NumPy
- scikit-learn
- gensim
- NLTK
- matplotlib
- Jupyter Notebook

## Notes

This project was developed as an NLP-based exploration of document clustering in the clinical domain. It demonstrates experience with text preprocessing, unsupervised learning, embedding-based representations, and research-oriented analysis.

## Future Improvements

- Add quantitative clustering metrics
- Extend to more advanced topic modeling methods
- Compare classical vector-space methods with transformer-based embeddings
- Improve reproducibility through modular scripts


### `requirements.txt`
A simple starting version:

```txt
pandas
numpy
scikit-learn
gensim
nltk
matplotlib
jupyter
