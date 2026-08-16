# Music Recommendation with K-Means

> **An unsupervised Machine Learning study exploring music clustering, dimensionality reduction, and recommendation using K-Means and Spotify-related data.**

This project investigates an earlier approach to recommendation based on **similarity and clustering** rather than personalized collaborative ranking.

The study combines data preparation, exploratory analysis, PCA, feature scaling, K-Means clustering, and Spotify integration to group songs with similar characteristics and use those groups as a basis for recommendations.

<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/K--Means-Clustering-green" alt="K-Means">
  <img src="https://img.shields.io/badge/PCA-Dimensionality%20Reduction-purple" alt="PCA">
  <img src="https://img.shields.io/badge/Spotify-Integration-1DB954?logo=spotify&logoColor=white" alt="Spotify">
</p>

---

## The idea

Music can be represented through numerical characteristics and metadata.

If songs with similar characteristics occupy nearby regions of a feature space, clustering can provide a simple way to organize the catalog and retrieve similar content.

The study asks:

> **Can unsupervised learning group songs into meaningful regions that can support a basic recommendation workflow?**

---

## Workflow

```text
Music Data
    ↓
Cleaning & Exploration
    ↓
Feature Scaling
    ↓
PCA
    ↓
K-Means Clustering
    ↓
Song / Genre Groups
    ↓
Similarity-Based Recommendation
    ↓
Spotify Integration
```

---

## Topics explored

- data cleaning and null-value checks;
- exploratory and correlation analysis;
- genre-level analysis;
- feature standardization with `StandardScaler`;
- dimensionality reduction with PCA;
- unsupervised learning with K-Means;
- cluster inspection and visualization;
- creation of a Machine Learning pipeline;
- recommendation based on clustered musical characteristics;
- Spotify / Spotipy integration;
- playlist and album-art retrieval in the notebook workflow.

---

## Repository artifacts

| Artifact | Purpose |
|---|---|
| [`Recomendação_de_música_com_K_Means.ipynb`](./Recomendação_de_música_com_K_Means.ipynb) | Complete analytical and recommendation workflow |
| [`Dados_totais.csv`](./Dados_totais.csv) | Main music dataset used by the study |
| [`data_by_genres.csv`](./data_by_genres.csv) | Genre-level data |
| [`data_by_year.csv`](./data_by_year.csv) | Year-level data |

---

## What this project demonstrates

- unsupervised Machine Learning;
- feature-space reasoning;
- PCA and dimensionality reduction;
- clustering with K-Means;
- integration of analytical logic with an external music service;
- transformation of clusters into a simple recommendation mechanism.

---

## Recommendation-system context

This project represents a **clustering-based recommendation experiment**.

It should not be interpreted as a modern personalized ranking system based on user-item interaction history.

Conceptually:

```text
This study
Music features → Clusters → Similar recommendations

Modern personalized recommender
User-item interactions → Candidate generation → Ranking → Top-K
```

The distinction is important because the two approaches solve different recommendation problems.

---

## Limitations

- recommendations are driven primarily by item characteristics and clustering;
- no explicit user-item interaction model is used;
- there is no offline Top-K ranking evaluation such as NDCG or MAP;
- cluster quality does not automatically imply recommendation quality;
- Spotify integrations may depend on API availability and credentials.

More recent recommendation studies in this portfolio explore ranking-oriented evaluation and personalized recommendation concepts.

---

## Author

**Rodrigo Terra**

Data & AI professional focused on Data Science, Artificial Intelligence, Analytics Engineering, and applied Machine Learning.

- GitHub: [Rodrigo Terra](https://github.com/rodrigorissettoterra)
- LinkedIn: [Rodrigo Terra](https://www.linkedin.com/in/rodrigo-rissetto-terra/)
