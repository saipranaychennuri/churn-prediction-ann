\# Customer Churn Prediction using ANN



\## Overview

Binary classification model to predict whether a bank customer will churn,

built using an Artificial Neural Network with TensorFlow/Keras.



\## Dataset

Churn Modelling dataset — 10,000 records with features like Geography,

Credit Score, Age, Balance, and Tenure.

Source: https://www.kaggle.com/datasets/shubh0799/churn-modelling



\## Tech Stack

\- Python, TensorFlow/Keras, Scikit-learn, Pandas, NumPy



\## Model Architecture

\- Input Layer → Hidden Layer 1 (6 neurons, ReLU) → Hidden Layer 2 (6 neurons, ReLU) → Output (Sigmoid)

\- Optimizer: Adam | Loss: Binary Crossentropy | Epochs: 100



\## Results

\- Accuracy: ~86% on test set



\## How to Run

1\. Download the dataset from Kaggle link above

2\. Install dependencies: pip install -r requirements.txt

3\. Open Churn\_ANN.ipynb in Jupyter or Google Colab

