# Breast-Cancer-Prediction-with-Neural-Networks

This project implements a basic neural network to predict breast cancer using the Wisconsin Breast Cancer Dataset. The model classifies tumors as malignant (cancerous) or benign (non-cancerous) based on numerical medical features.

## 📌 Project Overview
Breast cancer is one of the most common cancers in the world. Early detection significantly improves survival rates. This project utilizes a simple artificial neural network (ANN) to assist in breast cancer classification based on medical attributes.

## Dataset: Wisconsin Breast Cancer Dataset
The dataset used is the Wisconsin Breast Cancer Dataset (WBCD), which includes:

30 numerical features extracted from tumor cell nuclei
569 instances, labeled as:
Malignant (1) - Cancerous tumors
Benign (0) - Non-cancerous tumors

## Technologies Used
Python (for data processing and model training)
TensorFlow / Keras (for implementing the neural network)
Scikit-Learn (for data preprocessing and evaluation)
NumPy, Pandas (for data manipulation)
Matplotlib, Seaborn (for visualizing results)

## Model Architecture
The neural network is structured as follows:

Input Layer: 30 neurons (one for each feature)
Hidden Layers: Two dense layers with ReLU activation
Output Layer: 1 neuron with sigmoid activation (for binary classification)
Loss Function: binary_crossentropy
Optimizer: adam
Evaluation Metric: Accuracy

## Model Training Process
Data Preprocessing:

Standardized the data using StandardScaler
Split into training (80%) and test (20%) sets
Model Training:

Constructed a sequential ANN model using Keras
Used Adam optimizer for efficient learning
Evaluated using accuracy, precision, and recall

## Performance Evaluation:

Model achieved high accuracy on test data
Plotted loss and accuracy curves for analysis

