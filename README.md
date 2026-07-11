# MTBLS79 Metabolomics Clustering Analysis

## Project Overview

This project presents a comprehensive unsupervised learning analysis of the MTBLS79 metabolomics dataset. The objective was to investigate the underlying biological structure of the samples using multiple clustering algorithms and dimensionality reduction techniques.

The workflow includes exploratory data analysis, PCA and UMAP visualization, clustering using eleven different algorithms, and performance evaluation using both internal and external validation metrics.

---

## Dataset

**Dataset:** MTBLS79 (MetaboLights)

The dataset contains metabolomic profiles from three biological classes:

- C
- QC
- S

The data were standardized prior to dimensionality reduction and clustering.

---

## Project Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Principal Component Analysis (PCA)
4. Uniform Manifold Approximation and Projection (UMAP)
5. Clustering analysis
6. Cluster evaluation
7. Comparative analysis
8. Final interpretation

---

## Clustering Algorithms

The following clustering methods were evaluated:

- K-Means
- Hierarchical Clustering
- Gaussian Mixture Model (GMM)
- Spectral Clustering
- DBSCAN
- OPTICS
- HDBSCAN
- BIRCH
- Affinity Propagation
- Fuzzy C-Means (FCM)
- Self-Organizing Map (SOM)

---

## Evaluation Metrics

The clustering performance was evaluated using:

- Silhouette Score
- Adjusted Rand Index (ARI)
- Normalized Mutual Information (NMI)

---

## Main Findings

The comparison showed that:

- **K-Means**
- **Gaussian Mixture Model (GMM)**
- **Self-Organizing Map (SOM)**

achieved perfect agreement with the known biological classes:

| Metric | Value |
|--------|------:|
| ARI | 1.000 |
| NMI | 1.000 |

Although OPTICS and HDBSCAN produced higher Silhouette Scores, their agreement with the biological labels was lower.

---

## Repository Structure

```
Metabolomics-Clustering-Analysis
│
├── README.md
├── LICENSE
├── MTBLS79_Clustering_Analysis.ipynb
└── Metabolomics_Clustering_Report.pdf
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

```bash
jupyter notebook notebook/MTBLS79_Clustering_Analysis.ipynb
```

---

## References

The analysis was performed based on the MTBLS79 metabolomics dataset available from the MetaboLights repository.

---

## Author

**Sama Heidardoost**
