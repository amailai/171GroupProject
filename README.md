# Airbnb Review Rating Prediction

## Project Overview
This project predicts Airbnb listing review ratings using machine learning and deep learning models. The objective is to identify which listing features are associated with higher review scores and compare the performance of different predictive models.

## Dataset
The dataset consists of Airbnb listing information that was cleaned and preprocessed before model training. Features include listing characteristics, host information, pricing, and other attributes relevant to predicting review ratings.

## Models Implemented
The following models were developed and evaluated:

- Linear Regression
- Polynomial Regression
- Neural Network

Model performance was evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Repository Contents
- `171_Final_Project.ipynb` – Main Jupyter Notebook containing data preprocessing, exploratory data analysis, model development, and model evaluation.
- `ogdataset.csv` – Original Airbnb dataset used as the source data for the project.
- `processed_airbnb.csv` – Cleaned and preprocessed dataset used for training and testing the machine learning models.
- `processed_airbnb_all_reviews.csv` – Preprocessed dataset that incorporates Airbnb review information for additional analysis and modeling.

## Dataset

The dataset used in this project was obtained from Kaggle:

https://www.kaggle.com/datasets/navaneesh/airbnb/data

Data files © Original Authors.

## Running the Project

1. Install required packages:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Airbnb_Project.ipynb
```

3. Run all cells to reproduce the results.

## Author
Aaron Pilapil

Angelina Lai

Sia Puri

Zicheng Haung


## GitHub Repository
This repository contains all source code used for the project.
