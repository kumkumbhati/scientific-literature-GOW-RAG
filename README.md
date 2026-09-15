# Discovering Scientific Concept Relationships Through Graph-of-Words & RAG

# Scientific Literature Retrieval using Graph-of-Words

A research project exploring graph-based representations for retrieving relevant scientific evidence from research literature.

The project uses the **SciFact** dataset and compares a conventional dense retrieval approach with a ** Graph-of-Words**-based retrieval method.

## Research Question

Can relationships between words in scientific documents provide useful information for scientific claim and evidence retrieval?

## Pipeline

```
SciFact Dataset[cite: 1, 3]
       ↓
Data Preprocessing
       ↓
Dense Retrieval Baseline[cite: 3]
       ↓
Graph-of-Words Representation[cite: 3]
       ↓
Graph-based Retrieval[cite: 3]
       ↓
GNN / DGOW Experiments[cite: 3]
       ↓
Retrieval Comparison[cite: 3]
       ↓
RAG + Evaluation[cite: 3]
```

## Project Structure

```text
scientific-literature-gow-rag/[cite: 3]
├── data/[cite: 3]
├── notebooks/[cite: 3]
├── src/[cite: 3]
│   └── gow_rag/[cite: 3]
├── results/[cite: 3]
├── paper/[cite: 3]
├── tests/[cite: 3]
├── requirements.txt[cite: 3]
└── README.md[cite: 3]
```

## Dataset

The project uses the SciFact dataset from AllenAI, which contains scientific claims, research abstracts and evidence annotations.
The dataset is particularly useful here because evidence can be traced down to individual sentences within scientific documents.


## Technologies

Python-Pandas-NumPy-Jupyter-Hugging Face Datasets-Sentence Transformers-FAISS-NetworkX-PyTorch


## Author
Kumkum Bhati
Kumkum Bhati
BCA - Data Science
