# 🎬 Movie Recommendation System

A content-based movie recommendation system built using **Python**, **Pandas**, **Scikit-learn**, and **Natural Language Processing (NLP)**.  
This project recommends movies similar to a selected movie based on genres, keywords, cast, crew, and overview.

---

## 🚀 Features

- 🎥 Recommend similar movies instantly
- 🧠 Uses Content-Based Filtering
- 🔍 Movie similarity based on metadata
- 📊 NLP text vectorization using CountVectorizer
- 📁 Preprocessed dataset saved using Pickle
- ⚡ Fast recommendation engine

---

## 🛠️ Tech Stack

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **NLTK**
- **Pickle**

---

## 📂 Dataset Used

- TMDB 5000 Movies Dataset
- Files:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

---

## 🧠 How It Works

### 1️⃣ Data Preprocessing

Merged both datasets using movie title.

Selected important columns:

- movie_id
- title
- overview
- genres
- keywords
- cast
- crew

---

### 2️⃣ Feature Engineering

Created tags using:

- Overview
- Genres
- Keywords
- Top 3 Cast Members
- Director Name

Example:

```text
Avatar = action adventure fantasy future war alien jamescameron
