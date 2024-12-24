# Trustworthy Machine Learning & Poisoning Attacks: Federated Learning Defense Mechanism

This repository contains the implementation of our final project for **CS 484** on **Trustworthy Machine Learning and Poisoning Attacks**. The project explores how **data poisoning** can affect machine learning models, particularly in **Federated Learning (FL)** environments. We developed a novel defense strategy using **Local Differential Privacy (LDP)** and **K-means clustering** to detect and exclude malicious users from contributing to the global model, preserving user privacy while safeguarding the model’s integrity.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Technologies Used](#technologies-used)

## Project Overview
As Machine Learning (ML) becomes more widely used, the risks of attacks like data poisoning grow. This project focuses on defending against **poisoning attacks** in **Federated Learning (FL)**, where users with access to local data can intentionally introduce harmful data to degrade the performance of the global model.

We proposed a defense mechanism using **K-means clustering** and **Local Differential Privacy (LDP)** to identify and eliminate malicious data points, without compromising user privacy. The solution was tested on popular datasets like **MNIST** and **CIFAR-10**.

## Key Features
- **Data Poisoning Simulation**: A synthetic dataset was created, with malicious data points added randomly to simulate data poisoning.
- **K-means Clustering**: Used to cluster data points and identify anomalies based on silhouette scores.
- **Local Differential Privacy (LDP)**: Applied to monitor user loss during training to detect malicious behavior.
- **Model Evaluation**: Evaluated model performance using **accuracy** and **silhouette scores**.

## Technologies Used
- **Python**
- **Scikit-learn** (for machine learning and clustering)
- **NumPy** (for data manipulation)
- **Matplotlib** (for data visualization)

