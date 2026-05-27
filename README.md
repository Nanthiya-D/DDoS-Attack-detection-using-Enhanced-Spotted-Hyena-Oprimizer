# DDoS-Attack-detection-using-Enhanced-Spotted-Hyena-Oprimizer
DDoS-Attack detection using Enhanced Spotted Hyena Oprimizer

## Description

This repository contains the implementation of an Enhanced Spotted Hyena Optimizer (E-SHO) integrated with a Long Short-Term Memory (LSTM) network for Distributed Denial-of-Service (DDoS) attack detection in Internet of Things (IoT) environments. The proposed framework improves attack detection accuracy through optimized feature selection and hyperparameter tuning.

The model is evaluated using benchmark cybersecurity datasets including CICDDoS2019 and N-BaIoT. The framework combines deep temporal learning with swarm intelligence optimization to achieve improved classification performance, reduced false alarm rates, and enhanced robustness.

---

# Dataset Information

## Datasets Used

1. CICDDoS2019 Dataset
2. N-BaIoT Dataset

## Dataset Sources

* CICDDoS2019:
  https://www.unb.ca/cic/datasets/ddos-2019.html

* N-BaIoT:
  https://archive.ics.uci.edu/ml/datasets/N-BaIoT

## Dataset Format

The datasets are provided in CSV format containing:

* Network traffic features
* Flow statistics
* Attack labels
* Benign traffic samples

---

# Code Information

## Main Components

* Data preprocessing
* Feature scaling
* Label encoding
* Enhanced Spotted Hyena Optimization (E-SHO)
* LSTM model training
* Performance evaluation
* Accuracy visualization

## Files Included

* ESHO_LSTM_DDoS_Detection.ipynb
* dataset.csv
* README.md
* requirements.txt

---

# Usage Instructions

## Step 1: Install Dependencies

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib imbalanced-learn
```

## Step 2: Open Google Colab or Jupyter Notebook

Upload:

* Dataset file
* Notebook file

## Step 3: Run the Notebook

Execute all cells sequentially:

1. Dataset loading
2. Data preprocessing
3. Feature scaling
4. Model optimization
5. LSTM training
6. Performance evaluation

## Step 4: View Results

The notebook generates:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix
* Accuracy graphs

---

# Requirements

## Python Version

Python 3.9 or higher

## Required Libraries

* numpy
* pandas
* scikit-learn
* tensorflow
* matplotlib
* imbalanced-learn

---

# Methodology

The proposed methodology consists of the following stages:

1. Data Collection

   * Benchmark IoT datasets are collected.

2. Data Preprocessing

   * Missing value removal
   * Label encoding
   * Feature normalization

3. Feature Optimization

   * Enhanced Spotted Hyena Optimizer (E-SHO) is used for selecting optimal parameters and improving exploration–exploitation balance.

4. Deep Learning Classification

   * LSTM network captures temporal dependencies in network traffic.

5. Performance Evaluation

   * Metrics including accuracy, precision, recall, and F1-score are computed.

---

# Experimental Results

The proposed E-SHO-LSTM framework achieved competitive performance in IoT attack detection tasks with:

* High detection accuracy
* Reduced false positive rates
* Improved robustness against complex attack patterns

---

# Citation

If you use this work in your research, please cite:

Author(s), “E-SHO Optimized LSTM Framework for IoT DDoS Attack Detection,” Journal Submission, 2026.

---

# License

This project is intended for academic and research purposes only.

---

# Contribution Guidelines

Researchers and students are welcome to improve the framework by:

* Adding advanced optimization techniques
* Improving feature engineering
* Extending multiclass attack classification
* Testing on additional IoT datasets

