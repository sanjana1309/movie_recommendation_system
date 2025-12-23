# 🎬 Movie Recommender System

A **content-based Movie Recommender System** built using Machine Learning that suggests movies similar to a user-selected title.  
The application features an interactive **Streamlit web interface** and dynamically fetches movie posters using the **TMDB API**.

---

##  Features

-  Recommend **Top 5 similar movies** based on user selection  
-  Uses **Cosine Similarity** for content-based filtering  
-  Fast recommendations using **precomputed similarity matrix**  
-  Displays real-time movie posters via **TMDB API**  
- Clean and interactive UI built with **Streamlit**

---

##  Tech Stack

- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - Streamlit  
  - Scikit-learn  
  - Pandas  
  - NumPy  
- **API:** The Movie Database (TMDB)  
- **Model Storage:** Pickle  

---

##  Project Workflow

1. Movie metadata is processed and vectorized.
2. **Cosine similarity** is computed between movie feature vectors.
3. Similarity scores are stored for fast inference.
4. User selects a movie from the dropdown.
5. System returns the **top 5 most similar movies**.
6. Movie posters are fetched dynamically using TMDB API.

