# Movie Recommendation System

This project builds a **movie recommendation system** that suggests movies to users based on their past ratings and the preferences of similar users.  
It demonstrates how **Collaborative Filtering** techniques can be applied to real-world user–item interaction data.

---

## Project Overview
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

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Mohammad-Jaafar/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
You can open the notebook in Jupyter or Google Colab:
```bash
jupyter notebook Movie_Recommendation_System.ipynb
```
Or upload it directly to [Google Colab](https://colab.research.google.com/).

---

## Results & Demonstration
- Returns top **N recommended movies** for a given user ID.
- Supports both **User-Based** and **Item-Based** similarity (optional extensions).
- Demonstrates the use of **Matrix Factorization (SVD)** for dimensionality reduction.
- Includes **evaluation via Precision@K** for model performance.

---

## Future Improvements
- Add **hybrid filtering** (combine user-based and item-based).
- Integrate **content-based** features like genres and tags.
- Implement **model persistence** with joblib or pickle.
- Add a **modern web UI** (cards, posters, ratings).
- Enable **real-time personalization**.

---

## Author
**Mohammad Jaafar**  
mhdjaafar24@gmail.com  
[LinkedIn](https://www.linkedin.com/in/mohammad-jaafar-)  
[GitHub](https://github.com/mhdjaafar24)  
[HuggingFace](https://huggingface.co/mhdjaafar24)

---

*If you find this project useful, please give it a star on GitHub!* ⭐
