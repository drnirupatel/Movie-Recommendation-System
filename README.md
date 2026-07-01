# 🎬 Movie Recommendation System

## 📌 Project Overview
This project is a Content-Based Movie Recommendation System built using Python, Scikit-learn, and Streamlit. It recommends similar movies based on genres, cast, crew, keywords, and movie overviews.

## 📂 Dataset
- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit

## 🚀 Features
- Content-based recommendations
- Interactive Streamlit interface
- Fast similarity search
- User-friendly movie selection

## ▶️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Note

The file `similarity.pkl` is not included because it exceeds GitHub's 100 MB file size limit.

To generate it, run the notebook used for preprocessing and model creation.

## Dataset

This project uses the TMDB 5000 Movie Dataset.

You can download it from Kaggle:

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

After downloading, place these files in the project folder:

- tmdb_5000_movies.csv
- tmdb_5000_credits.csv
