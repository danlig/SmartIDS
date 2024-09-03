# SmartIDS

SmartIDS is a project that integrates Machine Learning techniques to improve the performance of Intrusion Detection Systems (IDS). The goal is to create smarter and more efficient IDS models capable of detecting cybersecurity threats and anomalies in network traffic.

## Overview

This repository contains code and resources developed as part of a research thesis that explores the application of various machine learning models to intrusion detection. The project evaluates models such as Naive Bayes, Logistic Regression, Random Forest, MLP, and others to identify the best approaches for improving IDS accuracy.

## Datasets

The SmartIDS project relies on publicly available intrusion detection datasets to train and evaluate the machine learning models. Below are the datasets used and instructions on how to download them.

### 1. NSL-KDD Dataset

The NSL-KDD dataset is an improved version of the original KDD Cup 1999 dataset, which addresses some inherent issues such as redundant records. It is widely used for network intrusion detection tasks.

- **Download Link**: [NSL-KDD Dataset](https://www.kaggle.com/datasets/hassan06/nslkdd/data)
- **Instructions**:
  1. Visit the download page.
  2. Download the `KDDTrain+.txt` and `KDDTest+.txt` files.
  3. Place them in the `datasets/nslkdd/` directory within the project.

### 2. CICIDS 2017 Dataset

The CICIDS 2017 dataset includes real-world network traffic and reflects current attack strategies. It is generated by the Canadian Institute for Cybersecurity and contains detailed information on several types of attacks.

- **Download Link**: [CICIDS 2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)
- **Instructions**:
  1. Go to the download page.
  2. Download the dataset files (e.g., CSV format).
  3. Extract the files and move them to the `datasets/cicids2017/` directory

## Key Features

- **Binary and Multi-class Classification**: Evaluate the performance of different machine learning models on binary (Benign vs. Malicious) and multi-class (specific attack types) classification tasks.
- **Cross-validation**: Stratified cross-validation is used to ensure the robustness of the models and prevent overfitting.
- **XGBoost**: Includes evaluation of the XGBoost algorithm for its performance in intrusion detection tasks.
- **GridSearch**: Utilizes GridSearch for hyperparameter tuning to optimize model performance.
- **Comprehensive Analysis**: The results include accuracy, precision, recall, and F1-score metrics for each model, providing insights into the strengths and weaknesses of each approach.
- **Scalable**: Designed to handle large datasets, making it applicable to real-world network traffic analysis.

## Models Evaluated

1. **Naive Bayes**
2. **Logistic Regression**
3. **Linear Discriminant Analysis**
4. **Random Forest**
5. **MLP (Multilayer Perceptron)**

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/danlig/SmartIDS.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SmartIDS
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Acknowledgments

This project was developed as part of the thesis relative to my Computer Science degree. Special thanks to all who contributed to the research and development of SmartIDS.
