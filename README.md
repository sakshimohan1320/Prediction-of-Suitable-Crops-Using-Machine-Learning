# Prediction of Suitable Crop Using Machine Learning

## Overview

This project addresses the critical challenge of crop yield prediction for farmers by leveraging machine learning techniques. By analyzing environmental factors such as temperature, rainfall, humidity, and soil nutrients, the system predicts the most suitable crop for a given set of conditions. The goal is to provide farmers with a decision-making tool to optimize yield and improve agricultural efficiency.

The system integrates multiple machine learning algorithms, compares their performance, and delivers predictions through a user-friendly web application.

---

## Features

1. **Data-Driven Crop Recommendations**:
   - Uses a dataset of 22 crop varieties with features like nitrogen, phosphorus, potassium, pH, temperature, humidity, and rainfall.
   
2. **Machine Learning Models**:
   - Implements and compares multiple algorithms including:
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Logistic Regression
     - Naive Bayes
     - XGBoost
   - Random Forest achieved the highest accuracy among tested models.

3. **Web-Based Interface**:
   - An interactive front-end module connects users to the prediction engine, allowing farmers and stakeholders to easily access results.

4. **Performance Evaluation**:
   - Compares model accuracies using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and accuracy percentage.

---

## System Architecture

1. **Machine Learning Module**:
   - Handles data preprocessing, model training, and prediction.
   
2. **Front-End Module**:
   - Provides an interface for users to input environmental factors and receive predictions.

---

## Future Enhancements

- Expand the dataset by integrating real-time environmental data.
- Incorporate additional factors like wind speed, altitude, fertilizers, and pest conditions.
- Enhance the prediction system with deep learning models like CNN and ANN.
- Enable real-time notifications for farmers through an integrated messaging module.

---

## Contributors

- Shranay Shahane
- Sakshi Dongre
- Nihaal Shetty

Under the guidance of:
- Dr. Himangi Pande
