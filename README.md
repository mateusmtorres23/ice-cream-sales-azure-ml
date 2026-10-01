# Ice Cream Sales — Azure Machine Learning

A machine learning project that predicts ice cream sales based on temperature using Linear Regression.

This project was my first hands-on experience with machine learning using scikit-learn and with training, registering, deploying, and consuming a model through Azure Machine Learning.

## Workflow

The project covers:

- Data preparation with Pandas
- Train/test splitting
- Linear Regression with scikit-learn
- Model evaluation using RMSE and R²
- Experiment and model tracking with MLflow
- Remote training with Azure Machine Learning
- Model registration
- Managed Online Endpoint deployment
- Model inference through the deployed endpoint

## Technologies

- Python
- scikit-learn
- Pandas
- NumPy
- MLflow
- Azure Machine Learning
- Jupyter Notebook

## Model

The model uses temperature as the input feature and predicts the expected number of ice cream sales.

The dataset is split into training and testing sets before fitting a Linear Regression model. RMSE and R² are calculated and logged through MLflow.

## Azure Machine Learning

The training script can be submitted as an Azure Machine Learning job.

After training, the resulting MLflow model is registered in Azure Machine Learning and deployed through a Managed Online Endpoint, allowing predictions to be requested remotely.
