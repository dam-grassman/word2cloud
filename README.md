# Word2Cloud : Wasserstein Word Embeddings

Notebook Viewer : https://nbviewer.jupyter.org/github/dam-grassman/word2cloud/blob/master/Wassertein_Embedding.ipynb

## Introduction 

The most common choice of for word emdedding are into Euclidean space where geometric characteristics (distances,angles) between vectors encode their level of association (Mikolov) but suffering from restrictive assumptions related to underlying graph properties (cluster size, sparsity). 
In this repo, we studied the paper *Learning Embeddings Into 
Entropic Wasserstein Spaces* by C. Frogner, F.Mirzazadeh and J.Solomon [2019] in which the proposed method aimed at embbed data as discrete probability distribution in a Wasserstein Space.

We propose in the notebook, an implementation of this new method applied to Word Embeddings.

## Outline

### 1. Word2Cloud : Wasserstein Word Embeddings 

- 1.1 Text8 Dataset
- 1.2 Negative Samping
- 1.3 Generator

### 2. Implementation


- 2.1 Sinkhorn Layer
 - 2.2 Word2Cloud
 - 2.3 Training

### 3. Results

- 3.1 Nearest Neighbors
 - 3.2 Visualisation
