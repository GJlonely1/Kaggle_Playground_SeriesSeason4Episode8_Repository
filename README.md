# Poisonous Mushroom Prediction

## Overview
This project is part of the 2024 Kaggle Playground Series - Season 4, Episode 8. The goal is to predict whether a mushroom is edible or poisonous based on its physical characteristics, using machine learning techniques.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Model Training](#model-training)
7. [Evaluation](#evaluation)
8. [Contributing](#contributing)
9. [License](#license)

## Project Description
This binary classification project aims to accurately predict the edibility of mushrooms using various machine learning models. We employ data preprocessing techniques, feature engineering, and hyperparameter tuning to achieve optimal performance.

## Installation
To set up the project environment, run:

```bash
pip install -r requirements.txt

``Usage``
To run the main script: python main.py

``Data Preprocessing``
Handling Missing Values
Outlier Detection using InterQuartile Range (IQR) method
Feature Transformation using Log Transformation
Feature scaling using MinMaxScaler
One-Hot Encoding (OHE) for Categorical Variables
Pipelines to automate manual preprocessing of data 

``Model Training``
We used the following model: LightGBM 

Hyperparameter Tuning was performed using Optuna and RandomizedSearchCV

``Evaluation``
Model was evaluated using the following metrics: 
    - Accuracy
Cross Validation is employed to ensure robust performance estimation. 

