# Anomaly-Detection-Autoencoders
Anomaly detection system for financial transactions using autoencoders, trained on the creditcard.csv dataset

# Anomaly Detection Using Autoencoders

## Overview
This research project uses **Autoencoders** for anomaly detection in time-series **financial transactions**, specifically for **fraud detection**. The model is trained on the **creditcard.csv** dataset.

## Dataset 📂
- The dataset is from Kaggle:
  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
## Implementation 🚀
- **Preprocessing:** Standardization, handling imbalanced classes, PCA transformation.
- **Model:** Deep autoencoder with encoder-decoder structure.
- **Training Strategy:** Only normal transactions used to train the autoencoder.
- **Evaluation:** Anomalous transactions detected based on reconstruction error.

## Results 📊
- **Accuracy:** 98%
- **Recall (Fraud Detection):** 88%
- **Precision:** 11%
- **F1-Score:** 0.20 (due to class imbalance)

## Running the Notebook 🛠️
To run the Colab notebook, click below:  
https://colab.research.google.com/drive/1fEAwXyXq_5-mSv2vIQtCabrMTuZasnOP
