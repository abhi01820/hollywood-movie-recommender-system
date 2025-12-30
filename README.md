# 🎬 Movie Recommendation System

A **content-based movie recommendation system** built using **Python**, **Bag of Words**, and **cosine similarity**, with an interactive **Streamlit web application**.

---

## 📌 Project Overview

This project recommends movies similar to a selected movie based on their content such as **overview, genres, keywords, and cast**.  
It uses **Natural Language Processing (NLP)** techniques to compute similarity between movies and suggest the most relevant ones.

The system is completely **unsupervised** and does **not require user ratings**.

---

## 🚀 Features

- Content-based movie recommendations
- Uses **Bag of Words** for text vectorization
- Cosine similarity to find similar movies
- Fast recommendations using precomputed similarity matrix
- Interactive **Streamlit UI**
- Displays movie posters
- Easy to deploy and extend

---

## 🧠 Machine Learning Approach

- **Type:** Unsupervised Learning
- **Technique:** Content-Based Filtering
- **Text Vectorization:** Bag of Words (CountVectorizer)
- **Similarity Metric:** Cosine Similarity

---

## 🛠️ Tech Stack

- **Python 3.11**
- **Pandas, NumPy**
- **Scikit-learn**
- **Streamlit**
- **Pickle**

---

## ⚙️ How It Works

1. Movie metadata is combined into a single text feature
2. Bag of Words converts text into numerical vectors
3. Cosine similarity is computed between movie vectors
4. Top similar movies are selected
5. Streamlit displays recommendations and posters

---
