# Netflix Content Clustering & Recommendation Engine

An end-to-end Unsupervised Machine Learning and NLP system designed to eliminate user choice paralysis by grouping Netflix titles based on semantic similarity and providing content-based recommendations without relying on user ratings or watch history.

---

## 📌 Problem Statement

Netflix houses over 7,000 titles, leading to user choice paralysis. Traditional metadata filters (e.g., generic genres) often miss cultural and thematic nuances, while collaborative filtering suffers from the **cold-start problem** for new users or newly released content. 

This project implements an unsupervised NLP pipeline that builds a unified "bag of content" representation (combining descriptions, cast, directors, genres, and production countries) to automatically cluster similar media and generate real-time recommendations.

---

## 🎯 Key Objectives

* **Exploratory Data Analysis:** Analyze distribution patterns across content types (Movies vs. TV Shows), country-level production, and target audience ratings.
* **NLP Preprocessing & Vectorization:** Clean, normalize, and convert multi-field text metadata into continuous high-dimensional vectors.
* **Dimensionality Reduction:** Compress vector spaces while preserving maximum variance for scalable computation.
* **Unsupervised Clustering:** Uncover latent content clusters using unsupervised algorithms evaluated with quantitative clustering metrics.
* **Content-Based Recommendation Engine:** Calculate similarity scores to retrieve relevant titles based on input content features.
* **Interactive Deployment:** Showcase recommendations via an interactive user interface.

---

## ⚙️ Tech Stack & Methodology

* **Languages & Core Libraries:** Python, Pandas, NumPy
* **NLP & Feature Extraction:** NLTK / Scikit-Learn (TF-IDF Vectorization, Text Cleaning, Stopword Removal)
* **Dimensionality Reduction & Clustering:** PCA / UMAP, K-Means / Agglomerative Clustering
* **Similarity Search:** Cosine Similarity
* **Visualization & Interface:** Matplotlib, Seaborn, Streamlit / Gradio

---

## 📊 Expected Outcomes & Business Impact

* **Cold-Start Resilience:** Generates recommendations immediately for new titles and users without requiring prior interaction history.
* **Enhanced Discoverability:** Surfaces long-tail catalog items that match granular thematic preferences (e.g., suggesting similar socio-cultural dramas based on input titles).
* **Privacy-Compliant:** Operates purely on content metadata, eliminating the need to store or track personal user behavioral data.

---

