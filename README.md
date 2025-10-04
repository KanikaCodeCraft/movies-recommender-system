# 🎥 Movie Recommendation System

This is a **content-based Movie Recommendation System** built using **Python, Scikit-learn, and Streamlit**.  
The system suggests movies similar to the one selected by the user, based on features like genres, cast, and description.  
It also displays **movie posters** fetched through the **TMDB API** to make the results visually appealing.

---

## 🚀 Project Overview

The goal of this project is to recommend movies that are similar to a given movie.  
It uses **machine learning techniques** and **natural language processing** to calculate the similarity between movies.

This project was developed during my **4-week internship training** as a practical implementation of the concepts learned in Python and Machine Learning.

---

## 🧠 Working Principle

1. **Data Preprocessing**
   - Movie data is loaded and cleaned.
   - Important columns like *title*, *overview*, *genres*, *cast*, and *crew* are selected.
   - Text data is combined into a single feature for each movie.

2. **Feature Extraction**
   - Used **CountVectorizer** from Scikit-learn to convert text into a matrix of word counts.

3. **Similarity Measurement**
   - Calculated **cosine similarity** between movies to find how closely related they are.

4. **Recommendation System**
   - When a user selects a movie, the app returns the top 5 most similar movies using the similarity matrix.

5. **Poster Fetching**
   - Used **TMDB API** to fetch and display movie posters alongside recommendations.

---

## 🧩 Technologies Used

| Category | Tools/Technologies |
|-----------|-------------------|
| Programming Language | Python |
| Libraries | pandas, numpy, scikit-learn, pickle, requests, streamlit |
| IDE | Jupyter Notebook, PyCharm |
| API | The Movie Database (TMDB) API |
| Frontend | Streamlit |

---
