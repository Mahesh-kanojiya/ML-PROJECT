# 🎬 Project: Movie Recommender System Using Machine Learning

<img src="demo/6.jpeg" alt="workflow" width="70%">

Recommendation systems are becoming increasingly important in today's digital world. They help users discover relevant content based on their interests while reducing the effort required to search through thousands of options.

This Movie Recommender System uses Machine Learning techniques to recommend movies that are similar to the user's selected movie. Recommendations are generated based on content similarity using the Cosine Similarity algorithm.

---

# 📌 Types of Recommendation Systems

## 1. Content-Based Filtering

- Uses movie attributes and features.
- Recommends movies similar to those previously liked by the user.
- Creates feature vectors for movies.
- Measures similarity using vector representations.
- Used by platforms like YouTube and Twitter.

**Advantages**
- Personalized recommendations.
- No dependency on other users.

**Limitations**
- Over-specialization.
- Difficult to recommend movies outside the user's interests.

---

## 2. Collaborative Filtering

- Based on user-item interactions.
- Finds users with similar preferences.
- Recommends movies liked by similar users.

**Advantages**
- Discovers new content.
- Doesn't require movie feature information.

**Limitations**
- Computationally expensive.
- Cold-start problem.
- Popularity bias.

---

## 3. Hybrid Recommendation System

- Combines Content-Based and Collaborative Filtering.
- Produces more accurate recommendations.
- Commonly used in modern recommendation systems.
- Uses embedding techniques such as Word2Vec.

---

# 📖 About the Project

This project is a **Streamlit-based Movie Recommendation Web Application** that recommends movies similar to the movie selected by the user.

The recommendation engine is built using **Content-Based Filtering** and **Cosine Similarity**.

---

# 🚀 Demo

<img src="demo/1.png" alt="demo" width="70%">

<img src="demo/2.png" alt="demo" width="70%">

<img src="demo/3.png" alt="demo" width="70%">

---

# 📊 Dataset Used

TMDB 5000 Movie Dataset

https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

---

# 🧠 Machine Learning Concept Used

## Cosine Similarity

Cosine Similarity is a mathematical metric used to determine how similar two vectors are.

### Working

1. Convert movie features into vectors.
2. Calculate cosine similarity between movie vectors.
3. Similarity score ranges between **0 and 1**.
4. Higher similarity score means movies are more similar.

Learn more:

https://www.learndatasci.com/glossary/cosine-similarity/

---

# 🛠️ Tech Stack

### Programming Language

- Python

### Machine Learning

- Scikit-learn

### Data Processing

- Pandas
- NumPy

### Web Framework

- Streamlit

### Model Serialization

- Pickle

### IDE

- Jupyter Notebook
- VS Code

---

# 📂 Project Structure

```
Movie-Recommender-System/
│
├── app.py
├── model.pkl
├── movie_list.pkl
├── requirements.txt
├── Movie Recommender System Data Analysis.ipynb
├── demo/
└── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Movie-Recommender-System.git
```

---

## Create Virtual Environment

```bash
conda create -n movie python=3.7.10 -y
```

Activate Environment

```bash
conda activate movie
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Generate Model Files

Run

```bash
Movie Recommender System Data Analysis.ipynb
```

This will generate:

- model.pkl
- movie_list.pkl

---

## Run the Application

```bash
streamlit run app.py
```

---

# ✨ Features

- Movie Recommendation System
- Content-Based Filtering
- Cosine Similarity
- Interactive Streamlit Interface
- Fast Movie Search
- Easy-to-use UI

---

# 📈 Future Improvements

- Hybrid Recommendation System
- User Authentication
- Personalized Recommendations
- TMDB API Integration
- Movie Posters and Trailers
- User Ratings

---

# 👨‍💻 Author

**Mahesh Kanojiya**

B.Tech CSE | IIIT Kota

Aspiring Data Analyst Enthusiast

### Skills

- Python
- SQL
- Machine Learning
- Pandas
- NumPy
- Scikit-learn
- Power BI
- Streamlit

# 🙏 Acknowledgements

This project is based on the TMDB Movie Dataset and inspired by open-source machine learning implementations available on GitHub. It has been adapted and maintained for learning and portfolio purposes.
