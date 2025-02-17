# ISUUPLY_Matching

# Product Matching with Machine Learning

## Overview

This project performs product matching using machine learning techniques. The model takes product descriptions, prices, and seller information to predict SKUs (Stock Keeping Units) for new products. It uses a **Logistic Regression** model trained with text features combined with numerical data (price).

## Features
- **Product Matching**: Predicts SKU based on product description and price.
- **Data Preprocessing**: Cleans and normalizes input text.
- **Model Training**: Logistic Regression model for SKU prediction.
- **Prediction Confidence**: Classifies prediction confidence (high, medium, low).

## Project Structure
The project contains several key components:
- **Data Preprocessing**: Cleans input text (removes special characters, normalizes price).
- **Model Training**: Trains a machine learning model to predict SKUs based on the product description and price.
- **Prediction Functionality**: Uses a trained model to predict SKUs for new input data.

---

## Requirements

To run this project, you need the following Python libraries:

- **pandas**: Data manipulation and analysis.
- **scikit-learn**: Machine learning tools for training models.
- **num2words**: Converts numbers to words (for Arabic text preprocessing).
- **joblib**: For saving and loading the trained model.
- **matplotlib** and **seaborn**: For visualizing data distributions.
- **re**: Regular expressions for text cleaning.

Install the required libraries by running:

```bash
pip install pandas scikit-learn num2words joblib matplotlib seaborn
