# The Housing Prices Challenge ReadMe

## Overview

This repository contains a Jupyter Notebook that addresses the Californian Housing Prices challenge from Kaggle. The goal of the challenge is to build a predictive model that determines the median housing price in California based on features such as population, median housing age, median income, households, etc. It is important to notice that this notebook derives from the Chapter 2 of the book Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurélien Géron.

## Repository Structure

The repository is organized as follows:

```
/housing-prices/
│
├── data/raw
│   ├── housing.csv
│
├── notebooks/
│   └── housing_prices.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

- `data/`: Contains the datasets provided by Kaggle for training and testing the model.
- `notebooks/`: Contains the Jupyter Notebook that walks through the problem-solving process.
- `README.md`: This file, describing the contents and usage of the repository.
- `requirements.txt`: Lists the dependencies required to run the notebook.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Running the Notebook

To run the notebook and reproduce the results, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/housing-prices.git
   cd housing-prices
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open and run the notebook:**

   In the Jupyter interface, navigate to `notebooks/housing-prices.ipynb` and run all cells to execute the code and reproduce the analysis and results.

## Project Description

The notebook is structured into several key sections:

1. **Data Loading and Exploration**: Loading the dataset and performing initial exploration and visualization.
2. **Data Preprocessing**: Cleaning the data, handling missing values, and feature engineering.
3. **Custom Tranforming**: Fitting and transforming data for manipulation.
4. **Transformation Pipelines**: Setting pipelines to help in transformation methods.
5. **Model Training**: Training various machine learning models and evaluating their performance.
6. **Model Evaluation**: Analyzing the performance of the models using various metrics and visualizations.
7. **Conclusion**: Summarizing the findings and the performance of the best model.
8. **Saving the Model**: Serializing the trained model for future use.

## Running Tests

To ensure the integrity of the project, you can run the tests included in the repository. Follow these steps:

1. **Install testing dependencies:**

   ```bash
   pip install pytest
   ```

2. **Run the tests:**

   ```bash
   pytest
   ```

The tests will automatically discover and run any test files in the repository, ensuring that the data processing, model training, and evaluation steps are functioning correctly.

---

Feel free to reach out if you have any questions or need further assistance!