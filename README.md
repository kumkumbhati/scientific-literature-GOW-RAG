# Discovering Scientific Concept Relationships Through Graph-of-Words & RAG

# Scientific Literature Retrieval using Graph-of-Words

A research project exploring graph-based representations for retrieving relevant scientific evidence from research literature.

The project uses the **SciFact** dataset and compares a conventional dense retrieval approach with a ** Graph-of-Words**-based retrieval method.

## Research Question

Can relationships between words in scientific documents provide useful information for scientific claim and evidence retrieval?

## Pipeline

SciFact Dataset
      ↓
Data Preprocessing
      ↓
Dense Retrieval Baseline
      ↓
Graph-of-Words Representation
      ↓
Graph-based Retrieval
      ↓
GNN / DGOW Experiments
      ↓
Retrieval Comparison
      ↓
RAG + Evaluation


## Project Structure 
scientific-literature-graph/
│
├── data/
├── notebooks/
├── src/
│   └── gow_rag/
├── results/
├── paper/
├── tests/
├── requirements.txt
└── README.md


## Dataset

The project uses the SciFact dataset from AllenAI, which contains scientific claims, research abstracts and evidence annotations.
The dataset is particularly useful here because evidence can be traced down to individual sentences within scientific documents.


## Technologies

Python-Pandas-NumPy-Jupyter-Hugging Face Datasets-Sentence Transformers-FAISS-NetworkX-PyTorch


## Author
Kumkum Bhati
BCA - Data Science
