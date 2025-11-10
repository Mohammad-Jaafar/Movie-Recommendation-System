# Movie Recommendation System

This project builds a **movie recommendation system** that suggests movies to users based on their past ratings and the preferences of similar users.  
It demonstrates how **Collaborative Filtering** techniques can be applied to real-world user–item interaction data.

---

## Overview
The goal of this project is to:
- Explore and analyze the **MovieLens 100K** dataset from kaggle.
- Implement **User-Based Collaborative Filtering** using **Cosine Similarity**.
- Evaluate the recommender system using **Precision@K**.
- Build a **web app** using **Gradio** and deploy it on **Hugging Face Spaces**.

---

## Machine Learning Techniques Used
- **Collaborative Filtering (User-Based)** – recommends items by finding similar users using cosine similarity.
- **Matrix Factorization (SVD)** – dimensionality reduction approach to capture latent relationships.
- **Evaluation Metric:**
  - Precision@K – measures how many of the top-K recommended movies are relevant.

---

## Dataset
- **Source:** [MovieLens 100K Dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)
- **Files Used:**
  - `u.data` → user–movie ratings (user_id, movie_id, rating, timestamp)
  - `u.item` → movie titles and metadata
- **Target:** Recommend top movies for each user.
- **Features:** Implicit user–item interactions (ratings).


---

## Project Structure
```
Movie-Recommendation-System/
│
├── Movie_Recommendation_System.ipynb
├── requirements.txt
├── ml-100k/
│   ├── u.data
│   └── u.item
└── README.md
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohammad-Jaafar/Movie-Recommendation-System.git
   ```
2. Open the notebook in Jupyter or Google Colab.
3. Run all cells step-by-step to reproduce the results.
---

## Results & Demonstration
- Returns top **N recommended movies** for a given user ID.
- Supports both **User-Based** and **Item-Based** similarity (optional extensions).
- Demonstrates the use of **Matrix Factorization (SVD)** for dimensionality reduction.
- Includes **evaluation via Precision@K** for model performance.

---

## Author
**Mohammad Jaafar**  
mhdjaafar24@gmail.com  
[LinkedIn](https://www.linkedin.com/in/mohammad-jaafar-)  
[HuggingFace](https://huggingface.co/Mhdjaafar)  
[GitHub](https://github.com/Mohammad-Jaafar)

---

*If you find this project useful, please give it a star on GitHub!* ⭐
