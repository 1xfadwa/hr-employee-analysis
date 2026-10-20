# Data

**Dataset:** Human Resources Data Set (HRDataset_v14.csv)

**Source:** Kaggle, https://www.kaggle.com/datasets/rhuebner/human-resources-data-set

**Author on Kaggle:** rhuebner

**License (as listed on Kaggle):** Data files © Original Authors.

## Why the data file is not in this repository

The license listed on Kaggle does not grant permission to redistribute the data files, so the CSV (and a `.pbix` file, which embeds a full copy of it) is not included here. All credit for the data belongs to its original authors. See the Kaggle page for the full and current terms.

## How to reproduce the analysis

1. Download the dataset from the Kaggle link above (a free Kaggle account is required).
2. Save `HRDataset_v14.csv` in this folder (`data/`).
3. Load it in Power BI Desktop (Get data > Text/CSV > Transform Data) and follow the cleaning steps described in the main [README](../README.md).
4. Add the measures from [`measures.dax`](../measures.dax).
