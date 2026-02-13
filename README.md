
Clustering Mixed-Type Data Using Partition-Based Algorithms

📌 Overview
This repository contains the implementation and analysis , which focuses on comparing partition-based clustering algorithms on mixed-type datasets (numerical and categorical data).
The study evaluates the performance of K-Means, K-Modes, and K-Prototypes using several clustering validity indices, with an emphasis on interpretability and suitability for mixed data scenarios.

🎯 Research Objectives
To apply partition-based clustering algorithms on mixed-type datasets
To compare the performance of K-Means, K-Modes, and K-Prototypes
To evaluate clustering quality using internal validation metrics
To analyze and interpret the characteristics of each resulting cluster
Clustering Mixed-Type Data Using Partition-Based Algorithms

🧪 Methodology
1. Data Preprocessing
Separation of numerical and categorical features
Encoding categorical attributes where required
Normalization of numerical data for distance-based algorithms
2. Clustering Algorithms
K-Means: Applied to numerical features
K-Modes: Applied to categorical features
K-Prototypes: Applied to mixed-type features
3. Evaluation Metrics
Silhouette Coefficient
Dunn Index
Cluster centroid / mode interpretation

📊 Results & Analysis
Each algorithm is evaluated under multiple experimental settings. The analysis focuses on:
Cluster compactness and separation
Stability across different parameter settings
Interpretability of clusters
Detailed results and discussions can be found in the corresponding notebooks.
Characteristic responses for each algorithm

🛠️ Tools & Libraries
Python
NumPy, Pandas
Scikit-learn
kmodes
Matplotlib / Seaborn

📌 Notes
This repository is primarily notebook-driven for research and experimentation.
The src directory is reserved for potential refactoring into reusable modules.

👤 Author
Althaaf Ramadhan
Undergraduate Student – Informatics Engineering

📄 License
This project is intended for academic and educational purposes.
