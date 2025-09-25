---
layout: default
title: AI/ML Project Hub
---

# 🎯 Project Demo Hub

Welcome to my AI/ML project showcase. This site highlights my deployed machine learning demos, complete with working frontends, backends, and source code links.

---

## 📽️ 1. AIML - End-to-end Movie Recommendation System

A hybrid movie recommendation system built using **content-based filtering** and **collaborative filtering**, deployed as an interactive web application with **Streamlit**:

## **Key Features**

- **Customizable Hybrid Recommendations**:
   - Adjust weights for content-based and collaborative filtering to get tailored results.

- **Efficient Memory Usage**:
   - Precomputed cosine similarity matrix stored in a FAISS vector store for content-based filtering.
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

## 📽️ 2. AIML - Telco Customer Churn Prediction System

This project is an end-to-end machine learning system to predict customer churn for a subscription-based business. The goal is to identify users who are likely to cancel their service soon so that retention teams can take proactive action.:

## **Key Features**

- **Tenure buckets and binary flags**:
   - .

- **One-hot encoding for categorical features**:
   - .

- **Feature interactions (tenure/charges)**:
   - .
 
- **Resampling for class imbalance**:
   - .
 
- **Threshold tuning**:

<!-- 🔗 **Live demo:** [View App](https://movielens-3fxvogxfzafxcvmfccfbrd.streamlit.app/) -->
💻 **Source code & README.md:** [GitHub Repo](https://github.com/cdondi/aiml_telco_customer_churn)

---
## 📽️ 3. Azure Python Chatbot

This project implements a Retrieval-Augmented Generation (RAG) system using Azure services to create an intelligent Q&A system based on Python documentation. The system is now fully deployed to production with comprehensive monitoring, authentication, and automated deployment capabilities.

- **Containerized deployment** to Azure App Service using optimized Docker images
- **Azure Kubernetes Service (AKS) deployment** for container orchestration and learning
- **GitHub Actions CI/CD** with dual deployment workflows
- **Application Insights monitoring** with real-time dashboards and alerting
- **API authentication placeholder and rate limiting** protecting production endpoints
- **Production testing** completed with real Azure resources and performance validation
- **Multi-platform deployment strategy** with both App Service and AKS environments

🔗 **Live demo:** [View App](https://rag-app-production-clvd.azurewebsites.net) 
💻 **Source code:** [GitHub Repo](https://github.com/cdondi/azure_rag_mvp)

