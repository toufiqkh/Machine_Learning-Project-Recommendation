# Machine_Learning-Project-Recommendation
A Content-Based Movie Recommendation System using Python, Scikit-Learn, and Cosine Similarity


# Movie Recommendation System 🎬

A machine learning project that recommends movies based on content similarity.

## 📌 Project Overview
This project uses **Content-Based Filtering** to suggest movies. By analyzing movie metadata such as genres, keywords, cast, and director, the system calculates the mathematical similarity between films.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, NLTK
- **Algorithm:** Cosine Similarity
- **Vectorization:** CountVectorizer

## 🚀 How it Works
1. **Data Preprocessing:** Merges datasets and cleans nested JSON-like structures.
2. **Feature Engineering:** Combines overviews, genres, and credits into a single "tags" column.
3. **Vectorization:** Converts text tags into 5,000-dimensional vectors.
4. **Similarity Calculation:** Uses Cosine Similarity to find the closest neighbors to a given movie.

## 📊 Results
When a user inputs a movie title (e.g., *Avatar*), the system returns the top 5 most similar movies based on plot and cast.

## 📂 File Structure
- `Machine_Learning Project Recommendation.ipynb`: Main analysis and model building.
- `movie_details.csv`: Dataset containing movie metadata.
- `movie_title.csv`: Dataset containing titles and credits.
