# Breast-Cancer-prediction-

Project Description

The **Breast Cancer Prediction** project leverages machine learning and deep learning techniques to classify tumors as **Malignant (cancerous)** or **Benign (non-cancerous)** using the **Breast Cancer Wisconsin dataset**.  

This project demonstrates the **end-to-end workflow** of building a predictive model, including:

- **Data Preprocessing**: Cleaning the dataset, handling missing values, encoding categorical labels, and preparing features/targets.  
- **Train-Test Split**: Dividing the dataset into training and testing subsets to evaluate generalization.  
- **Feature Standardization**: Scaling features to ensure consistent ranges and improve neural network performance.  
- **Neural Network Architecture**: Building a sequential deep learning model with dense layers, ReLU activations, and a sigmoid output for binary classification.  
- **Model Compilation**: Using the Adam optimizer, binary crossentropy loss, and accuracy as the evaluation metric.  
- **Model Training (Fit)**: Training the model with validation monitoring to detect overfitting or underfitting.  
- **Model Evaluation**: Assessing performance on unseen test data to measure accuracy and reliability.  
- **Prediction**: Generating predictions for both test data and new unseen samples, enabling real-world applicability.  

Objectives
- Provide a transparent and reproducible ML pipeline for breast cancer prediction.  
- Achieve high accuracy while maintaining interpretability and robustness.  
- Demonstrate best practices in **data preprocessing, model training, and evaluation**.  
- Enable prediction on **new patient data** for practical use cases.  

Key Features
- End-to-end workflow from raw data to predictions.  
- Neural network implementation using **TensorFlow/Keras**.  
- Visualizations of training vs validation accuracy/loss.  
- Saved trained model (`.h5`) for reuse and deployment.  
- Example scripts for predicting new data samples.  
