# book-analysis-project
# 📚 Book Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0D1117?style=for-the-badge&logo=seaborn&logoColor=white)
![KMeans](https://img.shields.io/badge/Clustering-KMeans-green?style=for-the-badge)

> **Created with 💖 by Sanjli Agarwal**  
> “Books are a uniquely portable magic.” – *Stephen King*

---

## ✨ Project Overview

This project explores and clusters books based on their genres, average ratings, number of reviews, and reader engagement.  
We enrich a Goodreads dataset with external genre information and use **unsupervised machine learning (KMeans)** to uncover hidden patterns in reader preferences.

---

## 📁 Dataset

- **Source**: Goodreads + External Genre Dataset (from Kaggle)
- **Records**: ~10,000 books
- **Columns Used**: `title`, `authors`, `average_rating`, `ratings_count`, `work_text_reviews_count`, `genres`, etc.

---

## 🔍 Project Highlights

- ✅ Data Cleaning & Preprocessing
- 📊 Exploratory Data Analysis (EDA)
- 🎯 Genre-based Clustering (KMeans)
- 🔬 PCA for Dimensionality Reduction
- 🌈 Cluster Interpretation + Word Clouds
- 📌 Insights on Reader Behavior & Genre Popularity

---

## 📈 Visuals Included

- Average rating distribution
- Ratings count vs average rating scatterplot
- Genre frequency bar charts
- Clusters visualized using PCA (2D)
- Word clouds per cluster 
- Language vs rating trends

---

## 🧠 Tools & Libraries Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- scikit-learn (KMeans, PCA)
- WordCloud 
- Jupyter Notebook

---

## 📂 Folder Structure

- `Book_Analysis_Project.ipynb`: main notebook
- `books.csv`: original dataset
- `goodreads_data.csv`: genre data
- `output_plots/`: visualizations
- `requirements.txt`: Python libraries used
