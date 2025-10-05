# E-Commerce Text Classification
This project implements text processing and classification models in Python as part of a Foundations in Data Science course. It uses the [E-Commerce Text Classification dataset](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification) from Kaggle to classify item descriptions into predefined categories.

  

## Overview
The repository contains code for preprocessing e-commerce product descriptions and building machine learning models to predict their categories. The project demonstrates fundamental data science techniques, including text cleaning, feature extraction, and classification, making it a great resource for students and beginners in data science.

## Features
-  **Text Preprocessing**:
	- Tokenization, stopword removal, and stemming/lemmatization
	- Conversion of text data into numerical features (e.g., TF-IDF)
-  **Classification Models**:
	- Implementation of classification neural network with Keras
-  **Evaluation**:
	- Metrics such as accuracy and confusion matrix heatmap
-  **Dataset**:
	- Uses the [E-Commerce Text Classification dataset](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification) from Kaggle

## Installation
To run the project locally, follow these steps:
```bash
git clone https://github.com/papaya147/ecommerce-text-classification.git
cd ecommerce-text-classification
conda create --prefix ./env python=3.11
conda activate ./env
pip install -r requirements.txt
```

### Prerequisites
- Conda (recommended for environment management)
- Kaggle account to download the dataset
- Dependencies listed in `requirements.txt`
