# ARTI308-lab2

Project Summary: Phishing Website Detection

This repository contains the initial setup for a machine learning project aiming to automate the detection of malicious URLs using supervised learning techniques.

1. Dataset Description 
Source: Kaggle Open Datasets.
Format: Tabular CSV.
Features: Metadata and structural characteristics of website URLs.
Target Variable: Label (Categorical: Good vs. Bad).

2. Machine Learning Problem 
Problem Type: Classification.
Learning Goal: The model is expected to learn patterns in URL features to distinguish between benign and phishing websites.
Problem Statement: In digital forensics and network security, identifying malicious links is critical to preventing attacks. This project utilizes a classification approach to build a model that can automatically predict the safety of a URL, reducing the manual workload for security analysts.

3. Methodology 
As visualized in the included methodology diagram, the project follows these steps:
Dataset Selection & Loading: Identifying an open-source dataset and loading it via Pandas.
Data Preprocessing: Cleaning and preparing features for the model.
Train/Test Split: Dividing data into training and testing sets to validate performance.
Model Training: Applying algorithms such as Random Forest or Naive Bayes.
Model Evaluation: Measuring the success of the model using Accuracy, Precision, and Recall.


Tools & AI Attribution

Development Environment: Jupyter Notebook.
Data Manipulation: Python Pandas library.
Diagram Generation: The Methodology Diagram was designed and generated with the assistance of Gemini AI.
