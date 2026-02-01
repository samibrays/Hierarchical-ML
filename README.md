# Patient Segmentation Using Hierarchical Clustering

## Business Problem
Hospitals often lack clear segmentation of patients when no labeled outcomes exist.
This project applies **unsupervised machine learning** to identify clinically meaningful
patient groups based on demographics, vitals, labs, and utilization patterns.

## Objective
- Segment patients into risk-based clusters
- Identify high-utilization and high-risk groups
- Support population health and care management decisions

## Dataset
Synthetic medical dataset (500 patients) simulating:
- Demographics
- Vitals
- Lab results
- Hospital utilization
- Comorbidity burden

## Methods
- Feature engineering (Utilization Score, Metabolic Risk Index)
- Standardization
- Hierarchical clustering (Ward linkage)
- PCA & t-SNE for visualization

## Key Insights
- Clear separation between low-risk, metabolic-risk, and high-utilization patients
- Elderly patients with multiple comorbidities form distinct clusters
- Results align with clinical intuition and care management strategies

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- SciPy
- Matplotlib, Seaborn

## Results
Cluster outputs can be integrated into BI dashboards or hospital decision-support systems.

## Future Work
- Compare against K-Means and DBSCAN
- Add time-series utilization trends
- Deploy as API for real-time patient assignment
