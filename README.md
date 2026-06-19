# TET-ML-Analysis

Machine learning analysis of IHC H-score biomarkers for predicting Masaoka-Koga stage and WHO histological risk group in thymic epithelial tumors.

## Associated publication

Kitrou et al. "Machine Learning-Based Prediction of Masaoka-Koga Stage and WHO Risk Group in Thymic Epithelial Tumors Using Immunohistochemical H-Score Profiles." MDPI Diagnostics (under review).

## Contents

- `Kitrou_Masaoka_Nested_v4.ipynb` — Masaoka-Koga stage prediction analysis
- `Kitrou_WHO_Nested_v4.ipynb` — WHO histological risk group prediction analysis

## Requirements

Python 3.8 or higher. Install dependencies with:

pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib seaborn openpyxl

## Data

The H-score datasets (thymomas_with_all_epithelial_Hscores.xlsx and thymomas_WHO_with_subtype.xlsx) are not publicly available due to institutional data governance constraints. They are available from the corresponding author upon reasonable request and subject to ethical approval. Place the Excel files in the same directory as the notebooks before running.

## Usage

Open each notebook in Jupyter and run all cells sequentially. All results, figures, and CSV outputs are generated automatically.
