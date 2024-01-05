# Predict Bank Personal Loan

## Overview

This repository contains code for a data mining project focused on predicting personal loans in a bank. The project utilizes various machine learning algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Gaussian Naive Bayes, and Complement Naive Bayes. The dataset used for the project is named "Bank_Personal_Loan_Modelling1.csv."

## Project Structure

- **Notebook**: The main Python notebook is named `predict-bank-personal-loan.ipynb`. This notebook contains the entire code for data preprocessing, exploration, model training, and evaluation.

- **Dataset**: The dataset used for the project is stored in the file `Bank_Personal_Loan_Modelling1.csv`.

## Prerequisites

Make sure you have the required Python libraries installed by running:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
## Getting Started

1. **Clone this repository:**

    ```bash
    git clone https://github.com/2001Omayma/projet_DM_predict-bank-personal-loan.git
    cd projet_DM_predict-bank-personal-loan
    ```

2. **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook predict-bank-personal-loan.ipynb
    ```

3. Follow the steps in the notebook for data exploration, preprocessing, and model training.

## Model Comparison

The project evaluates the performance of different machine learning models:

- Logistic Regression: 96.36%
- K-Nearest Neighbors (KNN): 96.29%
- Gaussian Naive Bayes: 90.50%
- Complement Naive Bayes: 83.50%

The Logistic Regression model achieved the highest accuracy among the models.

## Data and Preprocessing

The initial dataset had features like Age, Experience, Income, Family, CCAvg, Education, Mortgage, and several others. Data preprocessing steps included handling missing values, transforming negative values, and addressing outliers.

## Conclusion

The project demonstrates the use of various machine learning algorithms to predict personal loans in a banking scenario. The Logistic Regression model, with a 96.36% accuracy, emerged as the most effective in this particular context.

Feel free to explore the Jupyter Notebook for detailed code and analysis.
