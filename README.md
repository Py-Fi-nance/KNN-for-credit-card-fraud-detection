# Credit Card Fraud Detection: K-Nearest Neighbors (KNN)
## Overview
This project demonstrates a simple yet effective approach to detecting fraudulent transactions using the K-Nearest Neighbors algorithm. The objective is to build a model that can accurately classify transactions in a given dataset as either fraudulent or non-fraudulent.

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/KNN)](https://github.com/Py-Fi-nance/KNN/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/KNN)](https://github.com/Py-Fi-nance/KNN/stargazers)

## Table of Contents
1. [Dataset](#dataset)
2. [Implementation Steps](#implementation-steps)
   - [Data Loading and Exploration](#data-loading-and-exploration)
   - [Data Pre-processing](#data-pre-processing)
   - [Data Splitting](#data-splitting)
   - [Data Scaling](#data-scaling)
   - [Modeling](#modeling)
   - [Evaluation](#evaluation)
   - [Visualization](#visualization)
3. [Results](#results)
4. [Conclusion](#conclusion)
5. [Contributing](#contributing)
6. [Contact Information](#contact-information)


## Dataset <a name="dataset"></a>
The `creditcard.csv` dataset is utilized in this project. It consists of various anonymized features, along with `Time`, `Amount`, and `Class`, where `Class` indicates whether the transaction is fraudulent (`1`) or not (`0`).

## Implementation Steps <a name="implementation-steps"></a>
### Data Loading and Exploration <a name="data-loading-and-exploration"></a>
   The dataset is loaded, and initial exploration is performed to understand the data structure and content.
   Data Scource : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

### Data Pre-processing <a name="data-pre-processing"></a>
   Any rows with 'NaN' values in the 'Class' column are dropped to maintain data integrity.

### Data Splitting <a name="data-splitting"></a>
   The dataset is split into features (X) and the target variable (y), and further divided into training and test sets.

### Data Scaling <a name="data-scaling"></a>
   Feature scaling is performed using StandardScaler to standardize the dataset.

### Modeling <a name="modeling"></a>
   The K-Nearest Neighbors model is initialized, trained on the training data, and subsequently used to make predictions on the test data.

### Evaluation <a name="evaluation"></a>
   Model performance is evaluated using a classification report and accuracy score, assessing its ability to classify transactions correctly.

### Visualization <a name="visualization"></a>
   A confusion matrix is plotted as a heatmap, offering a visual representation of the model's performance, illustrating True Positives, True Negatives, False Positives, and False Negatives.

## Results <a name="results"></a>
The implemented model exhibits high accuracy, effectively differentiating between fraudulent and non-fraudulent transactions. It achieves an accuracy score of approximately `0.9996`.

## Conclusion <a name="conclusion"></a>
This K-Nearest Neighbors implementation serves as an efficient solution for credit card fraud detection, balancing simplicity with high accuracy. However, there is always room for further optimizations and enhancements to improve model adaptability and robustness, such as exploring different algorithms, tuning hyperparameters, and performing feature engineering.

## Contributing
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.


## Contact Information
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, KNN.
For a full article walkthrough please visit > https://www.pyfi.com/blog < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
