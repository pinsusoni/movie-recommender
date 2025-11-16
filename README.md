# 🎬 Movie Recommender System

## 🔍 Overview
This project builds a Movie Recommender System that suggests similar movies based on user-selected input. It uses content-based filtering with features like genres, keywords, cast, crew, and storyline descriptions to calculate similarity between movies.

## ⭐ Features
- Content-based movie recommendation
- Text preprocessing and feature engineering
- Vectorization using TF-IDF / CountVectorizer
- Cosine similarity for matching movies
- Easy-to-understand recommendation output

## 🧠 How It Works
1. Movie dataset is loaded and cleaned  
2. Important metadata is extracted:
   - Title  
   - Genres  
   - Overview  
   - Cast & Crew  
   - Keywords  
3. A combined "tags" column is created  
4. Text is converted into numerical form  
5. Similarity scores are generated  
6. Model returns the top recommended movies

## 📊 Techniques Used
- Feature Engineering  
- NLP preprocessing  
- Vectorization (TF-IDF / CountVectorizer)  
- Cosine Similarity  
- Content-Based Filtering  

## 🎥 Example Recommendation
**Input:**  
"Avatar"

**Output:**  
- Guardians of the Galaxy  
- Star Trek  
- John Carter  
- The Avengers  
- Prometheus  

(*Actual results depend on the dataset and similarity scores*)

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

## 🚀 How to Run
Open the file:  
**movieRecommender.ipynb**

## 📦 Dataset
Typical movie datasets include:
- TMDB movies & credits data  
- Title, genres, overview, keywords  
- Cast and crew information  

(Use any dataset the notebook supports.)

## 👤 Author
Prince Soni
