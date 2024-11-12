# Verif.ai: A Fraud Detection Platform for Secure Transactions

## Project Overview
Verif.ai is a comprehensive platform designed to detect fraudulent online transactions in real-time. Leveraging Optical Character Recognition (OCR) and machine learning, Verif.ai helps protect users from fraudulent sites by analyzing transaction data and providing instant fraud alerts.

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Solution Architecture](#solution-architecture)
3. [Model Overview](#model-overview)
4. [Technology Stack](#technology-stack)
5. [Future Scope](#future-scope)
6. [Getting Started](#getting-started)

## Problem Statement
With the rise of e-commerce, online financial fraud has become a pressing concern. Many users fall prey to fraudulent websites, resulting in financial losses. Verif.ai addresses this issue by offering a user-friendly platform that identifies fraudulent transactions through advanced fraud detection models.

## Solution Architecture
1. **Frontend**: Built with React for a responsive and intuitive user experience.
2. **Middleware**: Processes data received from the OCR and forwards it to the fraud detection model.
3. **Backend**: Developed with Express.js, it handles data routing and sanitization to ensure secure processing.
4. **Machine Learning Model**: A neural network that processes transaction data and predicts fraud probability.

### Key Features
- **OCR Data Extraction**: Users can upload transaction screenshots, and OCR technology extracts key transaction details.
- **Manual Data Entry Option**: Allows users to enter transaction details for custom data submissions.
- **Real-Time Fraud Detection**: Instantly alerts users if a transaction is detected as potentially fraudulent.

## Model Overview
Our model uses a neural network to predict the likelihood of a transaction being fraudulent:
- **Architecture**: Four-layer neural network with ReLU and sigmoid activations.
- **Performance Metrics**: The model outputs a Boolean value for fraud detection, with probability scoring.
- **Libraries**: TensorFlow, Scikit-learn, Pandas, and NumPy for model building, evaluation, and data manipulation.

## Technology Stack
- **Frontend**: React
- **Backend**: Express.js
- **Data Processing**: OpenAI OCR API, middleware for data extraction and formatting.
- **Machine Learning**: TensorFlow, Scikit-learn for model training and evaluation.

## Future Scope
- **Chrome Extension**: A browser extension to detect fraudulent websites in real time.
- **Dynamic Model Training**: Continuously improve model accuracy with new data, staying ahead of emerging fraud patterns.

## Getting Started
1. **Frontend**: Clone the [Frontend Repository](https://github.com/AkashSavanur/Fraud) and run `npm install` to set up dependencies.
2. **Backend**: Clone the [Backend Repository](https://github.com/AkashSavanur/FraudBackend) and run `npm install` for backend dependencies.
3. **OCR and Model Integration**: Connect with the OpenAI OCR API and configure the model for fraud detection.

## Authors
- **Team Members**: Aditya, Akash, Laksh, Shreyas

## License
This project is licensed under the MIT License.

