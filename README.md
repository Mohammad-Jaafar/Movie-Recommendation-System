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

## Features

-   Load and explore the MovieLens dataset
-   Implement **User-Based** and **Item-Based Collaborative Filtering**
-   Apply **Matrix Factorization (SVD)** for latent feature extraction
-   Evaluate recommendations using **Precision@K**
-   Build an interactive **Gradio web app**
-   Visualize recommended movies for given users

---

## Technologies Used

-   **Python 3.9+**
-   **Pandas / NumPy**
-   **Matplotlib / Seaborn**
-   **Scikit-learn**
-   **Surprise** (optional for SVD)
-   **Gradio** (for web app)

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

*If you find this project useful, please give it a star on GitHub!*
