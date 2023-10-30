# Taxi Tip Prediction using Scikit-Learn and Snap ML

## Overview

The "Taxi Tip Prediction" project focuses on predicting tip amounts for taxi trips by harnessing the capabilities of Scikit-Learn and Snap ML. This README provides a comprehensive guide to the project, from its structure to usage and results.

## Project Structure

The project is organized as follows:

- **data/**: This directory houses the dataset ('taxi_data.csv') used for training and evaluation.

- **src/**: Within this directory, you'll find Python scripts that handle different aspects of the project.

  - **data_preprocessing.py**: This script manages data preprocessing, including feature engineering and data splitting.

  - **scikit_learn_model.py**: In this script, a tip prediction model is trained using Scikit-Learn.

  - **snap_ml_model.py**: This script is dedicated to training a tip prediction model using Snap ML, known for accelerated training on both CPU and GPU.

- **README.md**: The very document you're reading, providing in-depth information and guidance.

## Data Preprocessing

Data preprocessing is an essential step that ensures the dataset is clean and well-prepared for model training. This stage includes the following key tasks:

- Conversion of date-time columns to datetime objects.
- Extraction of pickup and dropoff hours and days of the week.
- Calculation of trip time in seconds.
- Optional reduction of the dataset size for improved memory management.

For a detailed walkthrough and code samples of the data preprocessing tasks, please refer to the [Data Preprocessing section](#data-preprocessing) in this README.

## Model Training

The heart of the project is the training of tip prediction models using both Scikit-Learn and Snap ML. Both models are based on Decision Tree Regressors with specific hyperparameters.

### Scikit-Learn Model

The Scikit-Learn script trains a tip prediction model using the Scikit-Learn library, a powerful and widely-used machine learning tool.

### Snap ML Model

In the Snap ML script, we leverage Snap ML's accelerated training capabilities for training a tip prediction model on both CPU and GPU.

For step-by-step instructions and code snippets related to model training, please consult the [Model Training section](#model-training) in this README.

## Usage

To utilize the "Taxi Tip Prediction" project effectively, follow these steps:

1. Ensure that you have all the required dependencies installed. This includes Python, Scikit-Learn, Snap ML, NumPy, and Pandas.

2. Place your dataset file ('taxi_data.csv') in the 'data/' directory.

3. Customize the Python scripts within the 'src/' directory for your specific data preprocessing and model training needs.

4. Execute the Python scripts to preprocess the data and train tip prediction models using both libraries.

For precise usage instructions, please explore the [Usage section](#usage) in this README.

## Snap ML vs. Scikit-Learn Comparison

The project includes a comprehensive comparison between Snap ML and Scikit-Learn, covering training speedup and model evaluation. Here's what we found:

- Training speedup, calculated as the ratio of training times between Snap ML and Scikit-Learn.

- Model evaluation using Mean Squared Error (MSE) for both Snap ML and Scikit-Learn models, providing insights into their predictive accuracy.

For detailed results and insights, please refer to the [Snap ML vs. Scikit-Learn Comparison section](#snap-ml-vs-scikit-learn-comparison) in this README.

## Conclusion

The "Taxi Tip Prediction" project showcases the potential of Scikit-Learn and Snap ML for tip prediction tasks. By comparing the two libraries, you can make informed decisions about which one best aligns with your machine learning needs.

We welcome questions, suggestions, and collaboration opportunities. Happy coding!

*Note: Ensure that you have the necessary libraries and dependencies installed before running the project.*
