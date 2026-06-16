# Crypto Anomaly Detection
Comparative Analysis of Unsupervised Anomaly Detection Models for Cryptocurrency Transactions using the Elliptic Bitcoin Dataset.
# Cryptocurrency Transaction Anomaly Detection

## Project Overview

This project investigates the use of unsupervised machine learning techniques to detect anomalous cryptocurrency transactions using the Elliptic Bitcoin Dataset. The objective is to identify potentially illicit transactions by comparing multiple anomaly detection algorithms and evaluating their performance.

## Dataset

Dataset: Elliptic Bitcoin Dataset

The dataset contains Bitcoin transaction features, transaction classifications, and transaction network relationships.

Due to GitHub file size limitations, the original dataset is not included in this repository.

Dataset Source:
https://www.kaggle.com/datasets/ellipticco/elliptic-data-set

## Methodology

The following steps were performed:

1. Data preprocessing and cleaning
2. Feature scaling using StandardScaler
3. Dimensionality reduction using PCA
4. Anomaly detection model implementation
5. Model evaluation and comparison
6. Hyperparameter optimization

## Models Evaluated

* Isolation Forest
* Local Outlier Factor (LOF)
* DBSCAN

## Final Optimized Model

Best Model: Optimized Local Outlier Factor (LOF)

Configuration:

* PCA Components: 30
* Number of Neighbors: 5
* Contamination Rate: 0.12

Performance:

| Metric    | Score  |
| --------- | ------ |
| Precision | 0.1491 |
| Recall    | 0.1833 |
| F1-Score  | 0.1644 |

## Repository Structure

```text
COEN807_Crypto_Anomaly_Detection/

├── figures/
├── notebooks/
├── presentation/
├── report/
├── results/
└── .gitignore
```

## Results

The optimized Local Outlier Factor model achieved the highest overall performance among all evaluated anomaly detection models. Experimental results demonstrated that local density-based anomaly detection methods are more effective for identifying suspicious cryptocurrency transaction patterns within the Elliptic Bitcoin Dataset.

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Author

Abbad Islam

COEN807 – Machine Learning Project
