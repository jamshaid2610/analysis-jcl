# Identifying Top Performers in the Durham Junior Cricket League (Under-13)

## Overview

This project applies **unsupervised learning** techniques to identify top-performing players in the Durham Junior Cricket League's Under-13 division. The aim is to provide a comprehensive analytical framework for evaluating player performance using modern machine learning techniques such as **Principal Component Analysis (PCA)**, **autoencoders**, and clustering algorithms.

---

## Project Objectives

1. Identify key performance metrics distinguishing top-performing players.
2. Cluster players based on their performance using **K-Means++** and **Hierarchical Clustering**.
3. Analyse correlations between performance metrics for deeper insights.

---

## Data Sources

The data was sourced from the [Durham Cricket County Junior League website](https://dcbjuniorlge.play-cricket.com/home). Two datasets were collected:
1. **Batting and Bowling Scorecards** 
2. **Ball-by-Ball Data**

---

## Methodology

### 1. Data Collection
- Used Python libraries like **Selenium** and **BeautifulSoup** to scrape data.
- Processed datasets to create scorecards for individual players.

### 2. Data Cleaning and Preprocessing
- Removed duplicates and inconsistent player names.
- Derived new performance metrics such as **Boundary Index (BI)** and **Consistent Score (CS)**.
- Scaled features using **log transformations** and normalized them for uniform analysis.

### 3. Dimensionality Reduction
- **Principal Component Analysis (PCA):** Reduced data dimensions while retaining key variance.
- **Autoencoders:** Captured non-linear relationships between features for robust clustering.

### 4. Clustering
- Applied **K-Means++** and **Ward’s Hierarchical Clustering** to group players by performance.

---

## Results

- Identified key performance clusters for batters and bowlers.
- Highlighted significant metrics, e.g., **Boundary Index** for batters and **Economy Rate** for bowlers.
- Provided actionable insights for team management to focus on player development.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn, Seaborn, Selenium, BeautifulSoup

---

## Key Findings

- Strong correlations were found among metrics such as **Boundary Index** and **Fast Scorer Score (FSS)**.
- Dimensionality reduction enhanced clustering accuracy and interpretability.
- Framework is adaptable for other age groups or cricket leagues.

---

## Future Work

- Extend the methodology to additional leagues and age groups.
- Incorporate advanced metrics like fielding performance.
- Explore the integration of supervised learning for predictive analysis.

---

## Acknowledgements

This project was completed as part of the **Master of Data Science: Social Analytics** programme at **Durham University**. Special thanks to **Dr. Peter G.P. Swift** for guidance and support.

---

## Contact

**Author:** Mohammad Jamshaid Iqbal  
**Email:** [mohammadjamshaidiqbal@gmail.com](mailto:mohammadjamshaidiqbal@gmail.com)  
