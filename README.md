# Netflix Content-Based Recommendation System (Machine Learning)

## 🎯 Project Overview
Built an end-to-end content-based recommendation engine using **Python**, **Natural Language Processing (NLP)**, and **Machine Learning** to suggest top similar movies and TV shows based on user preferences.

## 🛠️ Tech Stack & Algorithms
- **Language:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning / NLP:** Scikit-Learn (`TfidfVectorizer`, `linear_kernel` for Cosine Similarity)

## 💡 Key Highlights
- Cleaned and preprocessed 8,800+ Netflix titles by handling missing values and combining metadata (`genres`, `description`, `director`).
- Converted unstructured text descriptions into numerical feature vectors using **TF-IDF**.
- Computed pairwise similarity scores to accurately recommend the top 5 most relevant titles.
