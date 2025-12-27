# FAISS-Based-Spotify-Recommendation-Engine

This project implements a content-based music recommendation system using the Spotify dataset.
Given a selected song, the system recommends the top n most similar songs based on audio features using a vector database (FAISS).


![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat&logo=python&logoColor=white)
![Recommendation](https://img.shields.io/badge/System-Content--Based%20Filtering-FF9800)
![VectorDB](https://img.shields.io/badge/Vector%20DB-FAISS-009688)
![Similarity](https://img.shields.io/badge/Similarity-Vector%20Search-673AB7)
![Domain](https://img.shields.io/badge/Domain-Music%20Analytics-607D8B)
![Status](https://img.shields.io/badge/Status-Completed-2E7D32)


##  Project Overview

Music recommendation systems play a crucial role in enhancing user experience.  
In this project, we leverage **vector similarity search** to efficiently find songs that are similar to a user's selected track.

The workflow includes:
- Feature extraction from Spotify audio data
- Vector embedding creation
- Indexing using **FAISS**
- Similarity-based song recommendations

---

##  Recommendation Approach

- **Type**: Content-Based Filtering  
- **Similarity Metric**: Vector similarity (e.g., L2 / cosine similarity via FAISS)  
- **Recommendation Output**: Top 5 similar songs  

Each song is represented as a numerical vector derived from Spotify audio features such as:
- Danceability  
- Energy  
- Loudness  
- Tempo  
- Valence  
- Acousticness  
- Instrumentalness  

---

##  Tech Stack

- **Python**
- **Pandas & NumPy** – Data processing
- **Scikit-learn** – Feature scaling
- **FAISS (Facebook AI Similarity Search)** – Vector database
- **Jupyter Notebook**

Python
Pandas & NumPy – Data processing
Scikit-learn – Feature scaling
FAISS (Facebook AI Similarity Search) – Vector database
Jupyter Notebook
