# 📊 Customer Segmentation & Movie Rating Prediction  
_A Machine Learning Internship Project at Arch Technologies_

---

## 📌 Overview
This repository contains two machine learning projects completed during my internship at **Arch Technologies**.  
Both tasks demonstrate practical applications of **data preprocessing, machine learning models, and insights generation** for real-world business scenarios.

---

## 🚀 Tasks

### **Task 1: Customer Segmentation**
- **Objective:** Group customers into segments based on purchasing behavior.  
- **Approach:**  
  - Preprocessed the dataset (handled missing values, encoded categorical features, and scaled numerical data).  
  - Applied **KMeans Clustering**.  
  - Used **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.  
  - Visualized clusters using **PCA (Principal Component Analysis)** for 2D representation.  
- **Business Value:**  
  Helps businesses identify high-value customers, budget-conscious buyers, and niche segments to design **personalized marketing strategies**.  

---

### **Task 2: Movie Rating Prediction**
- **Objective:** Predict how a user might rate a movie they haven’t seen yet.  
- **Dataset Used:** [Rating Disposition 2023 (ratings.csv)](https://files.grouplens.org/datasets/rating-disposition-2023/ratings.csv)  
- **Approach:**  
  - Applied **Collaborative Filtering (Surprise library – SVD algorithm)**.  
  - Built a recommendation system that predicts ratings for unseen movies.  
  - Generated **Top-N movie recommendations** for each user.  
- **Note:** Since the dataset only contains `ratings.csv` (no `movies.csv`), recommendations are displayed using **movieId** instead of movie titles.  

---

## 📈 Results & Insights
- **Customer Segmentation:** Identified distinct customer groups to support **targeted marketing and retention strategies**.  
- **Movie Recommendation:** Built a collaborative filtering system that can **predict user ratings and suggest movies**, demonstrating potential for integration into streaming platforms.  

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, surprise  
- **Visualization:** Matplotlib, PCA plots  
- **Datasets:**  
  - Custom Customer Dataset (for segmentation)  
  - [Rating Disposition 2023 – ratings.csv](https://files.grouplens.org/datasets/rating-disposition-2023/ratings.csv)  

---

## 📂 Repository Structure
