# Kidney Disease Prediction Model

This repository contains a machine learning project aimed at predicting kidney disease from clinical data. The project utilizes a Jupyter Notebook to preprocess data, train models, and evaluate their performance.

## Project Overview

The project uses a dataset containing clinical parameters that might influence kidney disease. It features exploratory data analysis, data cleaning, and preprocessing steps, followed by the training of machine learning models to predict the presence of kidney disease.

## Dataset

The dataset used in this project contains various clinical features including age, blood pressure, specific gravity, albumin levels, etc. In total, there are 25 clinical features used to predict kidney disease.

## Files

- `Kidney Disease Prediction.ipynb`: Jupyter notebook containing the full pipeline of data preprocessing, exploratory data analysis, model training, and evaluation.
- `pre_processed_df_kidney_disease.csv`: The cleaned and preprocessed dataset ready for machine learning modeling.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the notebook:
1. Ensure you have Jupyter Notebook installed:
   ```
   pip install notebook
   ```
2. Start the Jupyter Notebook server:
   ```
   jupyter notebook
   ```
3. Open the `Kidney Disease Prediction.ipynb` notebook and execute the cells sequentially.

## Models Trained

- **Logistic Regression**: A baseline model with extensive preprocessing and hyperparameter tuning, achieving high accuracy.
- **Support Vector Machine (SVM)**: Utilized with ADASYN to handle class imbalance, providing competitive accuracy rates.

## Evaluation

The models were evaluated based on accuracy, precision, recall, and F1-score. The Logistic Regression model, in particular, showed promising results on the test set.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

---

Feel free to modify this README further to better fit your project's details or if additional sections are needed.
