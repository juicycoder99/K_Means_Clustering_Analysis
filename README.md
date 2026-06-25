# K-Means Clustering Analysis

K-means clustering with scikit-learn: studying the effect of initialization strategy, cluster count,
data distribution, and a discriminant-space projection.

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
jupyter notebook kmeans_clustering.ipynb
```

## Files

| File | Description |
|------|-------------|
| `kmeans_clustering.ipynb` | Full implementation and analysis, covering all five experiments |
| `PROJECT_BRIEF.pdf` | Project brief (goals, objectives, outcomes) |
