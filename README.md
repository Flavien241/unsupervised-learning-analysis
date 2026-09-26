# PCA and Clustering Analysis

Coursework notebooks covering exploratory multivariate analysis and unsupervised learning.

## What is included

- principal component analysis of monthly temperature profiles for French cities (`TP2_ACP.ipynb`);
- hierarchical clustering and PCA-based visualisation (`TP3_Clustering.ipynb`);
- silhouette-score analysis and cluster-balance discussion on the included datasets.

The clustering notebook includes experiments on `wdbc.csv` and `spamb.csv`. It explicitly discusses why a silhouette score must be interpreted alongside cluster structure and balance.

## Run

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook
```

Open either notebook from Jupyter. The necessary CSV files are included alongside them.

## Context

Academic coursework completed at Polytech Lyon. The notebooks document data-analysis methods and their interpretation rather than a production data pipeline.
