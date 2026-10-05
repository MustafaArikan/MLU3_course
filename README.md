# MLU3 Course

Exercise material for **MLU3 — Unsupervised Machine Learning**

## Setup

### 1. Clone the repository

```bash
git clone <repository-url>
cd MLU3_course
```

### 2. Install dependencies

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) if you don't have it:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Then set up the environment for the week you want to work on:

```bash
cd week_0
uv sync
```

## Weeks

| Week | Topic | Exercises |
|------|-------|-----------|
| [week_0](week_0) | Clustering warm-up: k-means vs k-medoids | `make_blobs`, k-means|

## Datasets

* **Synthetic blobs** — generated with [`sklearn.datasets.make_blobs`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html).
  No download required, and the ground truth is known so that we can deliberately hide it.

## Notes

* Every week is its own `uv` project, with its own `pyproject.toml` and lock file.
* Notebook outputs are not committed, run the notebooks yourself.
