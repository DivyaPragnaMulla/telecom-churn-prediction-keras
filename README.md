Telecom Churn Prediction using Keras

Overview

In this project, I built a deep learning model using Keras to predict customer churn based on telecom usage data. The goal is to understand which customers are likely to leave a service and how machine learning can help identify such patterns.

---

Dataset

The dataset consists of telecom customer information, including:

- Call failure
- Complaints
- Subscription length
- Charge amount
- Customer value

The target variable is Churn, which indicates whether a customer has left the service (1) or not (0).

---

Problem

This is a binary classification problem:

- 0 → Customer stays
- 1 → Customer churns

---

What I did

Data preparation

- Loaded and inspected the dataset
- Ensured all features are numeric
- Split data into training and testing sets

---

Feature scaling

- Applied standardization using "StandardScaler" to improve model performance

---

Model

I built a simple neural network using Keras:

- Input layer (based on number of features)
- Hidden layer with ReLU activation
- Second hidden layer with ReLU
- Output layer with sigmoid activation

Why these choices?

- ReLU helps learn non-linear patterns
- Sigmoid is suitable for binary classification
- Binary crossentropy is used as the loss function

---

Training

- Optimizer: Adam
- Loss function: Binary Crossentropy
- Metrics: Accuracy
- Trained over multiple epochs with validation split

---

Results

The model achieved good performance on the test data, with stable training and validation accuracy.

---

Observations

- The model learns patterns effectively from structured data
- Feature scaling improves convergence
- Neural networks can capture non-linear relationships better than simple models

---

📊 Visualizations

Training Accuracy

"Accuracy" (accuracy.png)

Training Loss

"Loss" (loss.png)

---

Tools and Libraries

- Python
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

Why this project matters

Customer churn prediction is important for businesses to retain customers and reduce revenue loss. This project shows how deep learning can be applied to real-world customer data for decision-making.

---

Future Improvements

- Add feature importance analysis
- Compare with traditional ML models
- Use larger datasets for better generalisation

---

About me

-Dr Divya Pragna MULLA
I am applying machine learning and deep learning techniques to solve practical problems and build real-world data science projects.

About me

-applying machine learning and deep learning techniques to solve practical problems and build real-world data science projects.
