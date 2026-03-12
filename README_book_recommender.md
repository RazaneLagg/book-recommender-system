# 📚 Library Book Recommender System

> Personalised book recommendation engine built from university library borrowing history using collaborative filtering and content-based approaches.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange?style=flat-square)
![Data Mining](https://img.shields.io/badge/Data%20Mining-Recommender-blue?style=flat-square)

---

## 📌 Overview

Recommendation systems are at the core of modern digital experiences. This project builds a **personalised book recommender** for a university library using real borrowing history data, implementing and comparing two classical filtering strategies.

---

## 🧪 Approaches

| Method | Description |
|---|---|
| **Content-Based Filtering** | Recommends books similar to what the user has borrowed before |
| **Collaborative Filtering** | Recommends books based on what similar users have borrowed |

---

## 📊 Dataset

| Property | Value |
|---|---|
| Records | 5,000+ borrowing history entries |
| Source | University library database |
| Features | Book metadata + borrowing history |

---

## 🔧 Pipeline

```
1. Data Loading        →  Parse borrowing history records
2. EDA                 →  Most borrowed books, user activity distribution
3. Similarity Matrix   →  Cosine similarity between books / users
4. Recommendation      →  Top-N suggestions per user
5. Evaluation          →  Qualitative: relevance & diversity of suggestions
```

---

## 📁 Project Structure

```
book-recommender-system/
├── book_recommender_system.ipynb   # Main notebook
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/razanelagagna/book-recommender-system
cd book-recommender-system
pip install pandas numpy scikit-learn jupyter
jupyter notebook book_recommender_system.ipynb
```

---

## 👩‍💻 Author

**Razane Lagagna** — Group project — ENSIA, 2024
