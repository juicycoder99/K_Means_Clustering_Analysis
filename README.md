# Data Mining (CS405/CS505) — Assignment 3: K-means

Coursework for **Data Mining (CS405/CS505)**, Bishop's University.

K-means clustering with scikit-learn, studying the effect of initialization, the number of
clusters, the data distribution, and a discriminant-space projection. The full solution, answering
all five questions, is in [`Assignment3_KMeans_Clustering.ipynb`](Assignment3_KMeans_Clustering.ipynb).

## Topics covered

- Generating five well-separated 3-D Gaussian groups and clustering them.
- Stability of random vs k-means++ initialization, measured with the adjusted Rand index.
- Effect of the number of clusters on the Rand index, and the inertia elbow plot.
- Clustering uniform (structureless) data and why the partition is unstable.
- The texture dataset (5500 × 40, 11 classes): K-means on the raw features vs after an LDA
  projection (ARI improves from ~0.46 to ~0.99).

The texture dataset is downloaded automatically via `fetch_openml('texture')`.

## Running it

```bash
pip install numpy matplotlib scikit-learn
jupyter notebook Assignment3_KMeans_Clustering.ipynb
```

## Files

| File | Description |
|------|-------------|
| `Assignment3_KMeans_Clustering.ipynb` | Full solution with answers to all 5 questions |
| `Assignment 3.pdf` | Assignment description |
