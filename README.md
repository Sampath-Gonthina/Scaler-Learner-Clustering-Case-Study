# Scaler Learner & Company Profiling using Clustering

This project applies unsupervised machine learning techniques to analyze and group learners based on their professional background. The dataset, provided by Scaler, includes anonymized details such as job position, CTC (current compensation), year of employment, and associated company. The goal is to uncover meaningful learner segments to support personalized education strategies.

---

## Objective

To perform clustering analysis using K-Means to:
- Identify learner segments based on career and compensation attributes
- Enable data-driven personalization of learning paths
- Provide insights for scalable talent engagement models

---

## Key Techniques

- **Data Preprocessing**
  - Handling null values
  - Encoding categorical variables
  - Feature scaling using StandardScaler

- **Clustering**
  - K-Means Clustering Algorithm
  - Elbow Method and Silhouette Score to find the optimal number of clusters

- **Dimensionality Reduction**
  - Principal Component Analysis (PCA) for 2D visualization

- **Visualization**
  - Scatter plots and cluster heatmaps to interpret segment patterns

---

## Dataset Overview

The anonymized dataset includes the following features:

| Feature | Description |
|---------|-------------|
| `email_hash` | Unique learner identifier |
| `company_hash` | Anonymized company name |
| `orgyear` | Year of employment |
| `CTC` | Current compensation |
| `job_position` | Role or position in the company |
| `CTC_updated_year` | Year the compensation was last updated |

---

## Results

- Identified 3–5 meaningful learner segments with distinct compensation and job role patterns.
- PCA visualization showed clear separation between clusters.
- Derived insights can guide:
  - Targeted learning recommendations
  - Cohort-based curriculum optimization
  - Scalable learner engagement strategies

---

## Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- PCA, K-Means

---

## Project Structure

```bash
scaler_clustering/
│
├── scaler_clustering.ipynb   # Complete notebook with code and analysis
├── README.md                 # Project documentation
└── clustering_outputs/       # (Optional) Visualizations and results
