# Expedia User Segmentation (Clustering Project)

This project focuses on analyzing and grouping Expedia users based on their travel behavior using unsupervised machine learning techniques. The goal was to identify distinct traveler types by clustering users using K-Means and Agglomerative Clustering.

---

## 📂 Dataset

The dataset used contains anonymized Expedia user interactions, including information about booking status, destination, search dates, and other user-level attributes.

🔗 **Dataset Link:** [https://www.kaggle.com/datasets/jacopoferretti/expedia-travel-dataset]

---

## 🧠 Problem Statement

Travel platforms like Expedia have a wide range of users with different preferences and behaviors. By segmenting users based on how they interact with the platform (e.g., how early they book, how long they travel, how far they go), we can build targeted user profiles that help personalize recommendations, improve user experience, and guide marketing strategies.

---

## 🧰 What This Project Covers

- ✅ Data cleaning, handling of missing values, and type conversions
- ✅ Feature engineering (`travel_duration`, `days_in_advance`, `booking_ratio`, etc.)
- ✅ K-Means clustering on the full dataset
- ✅ Agglomerative clustering on a 40,000-user sample
- ✅ Dimensionality reduction using PCA for 2D and 3D visualizations
- ✅ Clustering evaluation using Silhouette Score and Davies-Bouldin Index
- ✅ Comparative analysis of cluster behavior (duration, distance, booking time)

---

## 🧾 Summary of Insights

The project revealed four clear user segments:

- **Early Planners:** Book well in advance, travel to nearby places
- **Balanced Family Travelers:** Plan moderately, travel mid to long distances
- **Long-Haul Explorers:** Travel the farthest and stay the longest
- **Last-Minute Travelers:** Book close to departure, short trips and nearby destinations

These segments were found consistently across both clustering techniques, with K-Means offering slightly better performance due to full-data access.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Scikit-learn)
- Seaborn & Matplotlib for visualization
- PCA for dimensionality reduction
- Silhouette & Davies-Bouldin Index for cluster evaluation

---

## 📌 Conclusion

This project demonstrates how behavioral clustering can be used to uncover user personas in a travel platform. These insights can be used for personalization, improved customer engagement, and targeted marketing strategies.

---
