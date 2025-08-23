## Movie Recommendation:
- Problem Statement: : Developed a content-based movie recommender system using cosine similarity to suggest movies with similar genres and user preferences
## Heroku link: https://manas-mrs.herokuapp.com/

# 🎬 Movie Recommendation Engine

A **Content-Based Movie Recommendation System** that suggests movies similar to a given movie using **cosine similarity** on movie metadata (genres, keywords, overview, etc.).  
Built with **Python, Pandas, NumPy, Scikit-learn, and Flask**, and deployed for interactive use.  

## Table of Contents
- Overview 
- Dataset
- Approach
- Tech Stack
- Features
- Results
- Deployment
- How to Run
- Future Improvements
- References

## Overview
This project implements a **content-based recommendation engine** that recommends top-N movies similar to a given movie.  
It uses **TF-IDF vectorization** of textual features and **cosine similarity** to find related movies.

##  Dataset
- Source: IMDb
- Contains metadata about movies:  
  - Title  
  - Genres  
  - Keywords  
  - Overview  
  - Cast & Crew  

## Approach
1. **Data Preprocessing**: Cleaning null values, selecting key features.  
2. **Feature Engineering**: Combined textual data (genres, overview, keywords).  
3. **Vectorization**: Applied **TF-IDF Vectorizer** to convert text to numerical form.  
4. **Similarity Calculation**: Used **Cosine Similarity** to compute similarity between movies.  
5. **Recommendation**: Ranked and displayed top-N most similar movies.  

## Tech Stack
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, NLTK  
- **Visualization**: Matplotlib, Seaborn  
- **Deployment**: Flask / Streamlit  
- **Cloud Hosting**: Heroku / Render *(if deployed)*  

##  Features
- Enter a movie title → get **Top 5 similar movies**  
- Works on metadata (genres, keywords, overview)  
- Interactive **web-based interface**  
- Lightweight and scalable  

## Results
Example Recommendations for *"Inception"*:
- Interstellar  
- The Matrix  
- Shutter Island  
- Memento  
- Minority Report  

## 🌐 Deployment
- Live Demo:Movie Recommender App: https://manas-mrs.herokuapp.com/ 


## How to Run

bash
# Clone repository
git clone https://github.com/yourusername/Movie-Recommendation.git

# Navigate to folder
cd Movie-Recommendation

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py


## Future Improvements
- Add Collaborative Filtering (user ratings)
- Hybrid recommendation (content + collaborative)
- Use deep learning embeddings (Word2Vec, Transformers)
- Improve UI with Streamlit / React

## References

- Kaggle Movie Dataset: https://www.kaggle.com/datasets
- Scikit-learn Documentation: https://scikit-learn.org/stable/
- Content-Based Recommendation Guide: https://towardsdatascience.com

Developed by Manas Kumar Bej
