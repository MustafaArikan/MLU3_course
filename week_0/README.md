# Week 0: Clustering using k-means

This week introduces clustering on **synthetic blobs**: data we generate ourselves, so
we control it and know the right answer.
## Project Structure

* **`00_Check_Environment.ipynb`**: Python and package version verification.
* **`01_Make_Blobs.ipynb`**: Generate the synthetic dataset, visualise it, add outliers, save to `data/`.
* **`02_KMeans.ipynb`**: k-means, centroids, the effect of outliers, choosing `k`.

## Technical Requirements

Managed via `uv`. Key dependencies:

* `scikit-learn` (clustering, metrics, dataset generation)
* `numpy`, `pandas` (data handling)
* `matplotlib` (visualisation)

## Workflow

1. **Generate**: all data comes from `make_blobs`. Two versions are kept — clean blobs,
   and the same blobs plus 15 outliers.
2. **Cluster**: k-means

## Usage

1. Run `uv sync` to install dependencies.
2. Execute the notebooks in order (00–02).

Notebook outputs are not committed.
