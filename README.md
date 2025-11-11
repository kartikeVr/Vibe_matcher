# 🎧 Vibe Matcher — AI-Powered Fashion Recommender

**Vibe Matcher** is a simple AI-based fashion recommendation system that matches a user's *vibe query* (like "boho chic" or "urban cool") to the most relevant fashion product descriptions using text embeddings and cosine similarity.

---

## 🧠 Project Overview

This project demonstrates how **text embeddings** can be used to build a *vibe-based recommendation system* for fashion items.

You enter a vibe (e.g., *"cozy countryside autumn"*) and the model finds the top matching fashion products that best fit that feeling — all done through semantic similarity.

---

## 🚀 Features

✅ Input your own *vibe queries* (moods, aesthetics, or styles)  
✅ Embeds text using `distilbert-base-uncased model`
✅ Computes similarity with `cosine_similarity` from `scikit-learn`  
✅ Returns top matching products with similarity scores  
✅ Logs and visualizes similarity metrics (optional)  

---

## 🧩 Tech Stack

| Component | Tool / Library |
|------------|----------------|
| Language | Python 3.11 |
| Embeddings | `distilbert-base-uncased`|
| ML / Math | NumPy, scikit-learn |
| Data Handling | Pandas |
| Visualization | Matplotlib (optional) |
| Environment | Arch Linux (Hyprland) + `uv` package manager |

---

