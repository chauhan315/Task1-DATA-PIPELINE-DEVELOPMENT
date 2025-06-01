*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: ANKUR SINGH CHAUHAN

*INTERN ID*: CT12WV42

*DOMAIN*: DATA SCIENCE

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTOSH

# Titanic Dataset ETL Pipeline

This project demonstrates a standard **ETL (Extract, Transform, Load) pipeline** using the Titanic dataset from OpenML. The goal is to prepare the dataset for machine learning models by handling missing values, encoding categorical variables, and standardizing numerical features. The pipeline is built using Python’s `scikit-learn` library and provides a clean and modular way to preprocess tabular data.

## Project Overview

The Titanic survival prediction problem is a classic binary classification task in machine learning. Each row in the dataset represents a passenger, and the task is to predict whether the passenger survived (`1`) or not (`0`) based on several features like age, class, gender, and more.

This project focuses on the data preprocessing stage, often referred to as ETL. The steps covered include:

- Extracting the dataset
- Separating features and target
- Identifying numeric and categorical columns
- Handling missing data
- Scaling numeric features
- Encoding categorical features
- Combining the transformations into a pipeline
- Applying the pipeline
- Splitting the data for model training and evaluation

## Dependencies

Make sure the following Python packages are installed:

```bash
pip install pandas scikit-learn openml
