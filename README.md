# Simple Content-Based Movie Recommendation System

## Overview
This project is a content-based movie recommendation system that suggests movies based on a user's textual input.  
It uses TF-IDF vectorization combined with cosine similarity to recommend movies based on their genre and tagline descriptions.  
This system returns the top 5 most similar movies from the IMDb Top 250 Movies Dataset.

---

## Dataset
**Source:** [IMDb Top 250 Movies Dataset (Kaggle)](https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset)

**Preprocessing Steps:**
1. **Columns Used:** `name` (movie title), `genre`, and `tagline`.
2. **Description Construction:** Combined `genre` and `tagline` for better content-based recommendations.
3. **Data Cleaning:** Removed missing values from the dataset.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/RohannnK/lumaa-spring-2025-ai-ml.git
cd lumaa-spring-2025-ai-ml

python3 -m venv env  # Create a virtual environment
source env/bin/activate  # Activate on macOS/Linux
env\Scripts\activate  # Activate on Windows

pandas
scikit-learn
jupyter

