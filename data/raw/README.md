# Raw Data

This folder is intended to store the **original raw datasets** used in the project before any cleaning or transformation.

## Dataset Source

The dataset used in this project comes from the **E-commerce Behavior Data from Multi-Category Store** available on Kaggle.

Dataset link:
https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

The original dataset contains millions of rows of user interaction data including:

* product views
* add-to-cart events
* purchases
* session information
* product categories
* prices and brands

## Why Raw Data Is Not Included

The full raw dataset is **not included in this repository** because it is too large for GitHub storage limits.

To keep the repository lightweight and easy to run:

* A **sample dataset (150,000 rows)** is provided in
  `data/sample/ecommerce_sample.csv`
* All analysis notebooks and scripts are designed to run using this sample.

## Reproducing the Raw Dataset

To reproduce the analysis with the full dataset:

1. Download the dataset from Kaggle.
2. Place the file inside this folder:

```
data/raw/
```

Example:

```
data/raw/2019-Oct.csv
```

3. Run the notebooks in order:

```
notebooks/01_data_loading_and_cleaning.ipynb
notebooks/02_funnel_analysis.ipynb
notebooks/03_retention_cohort_analysis.ipynb
notebooks/04_customer_segmentation.ipynb
notebooks/05_business_recommendations.ipynb
```

These notebooks will generate the processed datasets and outputs automatically.

## Project Structure Context

```
data/
├── raw/        → original large dataset (not included)
├── sample/     → lightweight dataset for reproducibility
└── processed/  → cleaned and aggregated outputs
```

The goal is to make the repository **reproducible while respecting GitHub file size limits**.

