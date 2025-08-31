---
layout: default
title: AI/ML Project Hub
---

# 🎯 Project Demo Hub

Welcome to my AI/ML project showcase. This site highlights my deployed machine learning demos, complete with working frontends, backends, and source code links.

---

## 📽️ Movie Recommendation System

A hybrid movie recommendation system built using **content-based filtering** and **collaborative filtering**, deployed as an interactive web application with **Streamlit**:

## **Key Features**

- **Customizable Hybrid Recommendations**:
   - Adjust weights for content-based and collaborative filtering to get tailored results.

- **Efficient Memory Usage**:
   - Precomputed cosine similarity matrix stored in HDF5 format for content-based filtering.
   - Optimized SVD for collaborative filtering.

- **Interactive Interface**:
   - Built with Streamlit for a user-friendly experience.

🔗 **Live demo:** [View App](https://movielens-3fxvogxfzafxcvmfccfbrd.streamlit.app/) 
💻 **Source code:** [GitHub Repo](https://github.com/cdondi/aiml_movie_recommendation)

1. **Enter a Movie Title**:
   - Input a movie title (e.g., `"Toy Story (1995)"`) to get recommendations.

2. **Optionally Enter a User ID**:
   - Provide a user ID to personalize recommendations using collaborative filtering.

3. **Adjust Weights**:
   - Use the sliders to control the balance between content-based and collaborative recommendations.

4. **Set Number of Recommendations**:
   - Choose how many recommendations to display.

5. **View Results**:
   - The app displays a list of recommended movies based on the inputs and settings.

---

More projects coming soon.
