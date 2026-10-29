
# Graph-Enhanced Fraud Detection under Data Scarcity

This repository contains the official Python code and supplementary materials for the research paper:

**"Graph-Enhanced Fraud Detection under Data Scarcity: An Empirical Study on Financial Transactions with Implications for the Iraqi Banking Sector"**

**Authors:** 
- Mohammed Ali Hussein Hathal (Department of Computer Science)
- Nabras Fadhil Hussein (Department of Finance and Banking)
- Uday Kadhim Hussein (Department of Finance and Banking)


---

## 📌 Project Overview
This project proposes a graph-enhanced machine learning framework to detect financial fraud. By constructing a 

relational graph where nodes represent card accounts and edges represent shared device information, we extract graph-based features (e.g., Graph Degree, Clustering Coefficient). These features are 

integrated with traditional tabular data to train a LightGBM classifier.

The empirical study demonstrates that graph-derived features improve the Precision-Recall AUC (PR-AUC) and rank among the 

top predictors in the model, offering a transferable blueprint for the Iraqi banking sector.

## 📊 Dataset
The dataset used in this study is the **IEEE-CIS Fraud Detection** dataset, 

publicly available on Kaggle. Due to size and licensing constraints, the data is not hosted in this repository. 

You can download the dataset (`train_transaction.csv` and 

`train_identity.csv`) directly from: 
[IEEE-CIS Fraud Detection on Kaggle](https://www.kaggle.com/competitions/ieee-fraud-detection/data)

## 🛠️ Requirements
To run the code, you will need the following Python libraries:
*   `pandas`
*   `numpy`
*   `networkx`
*   `lightgbm`
*   `scikit-learn`
*   `matplotlib`
*   `seaborn`

You can install them 

using:
```bash
pip install pandas numpy networkx lightgbm scikit-learn matplotlib seaborn
